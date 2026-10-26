# Guide 03 — Software

**CeleauPrinter 10 — Firmware, machine configuration and preparation tools**

> **Status:** content plan. The full version of this guide will be published together with the project's assembly documentation. This file describes what the guide will cover; it does not yet contain a step-by-step procedure.

---

## About this guide

This booklet covers the **software** part of the CeleauPrinter 10: the firmware that drives the machine, its configuration, the tools used to prepare print files and the diagnostic procedures. It is written for the person who installs, updates and parameterises the software associated with the CeleauPrinter 10.

**How this guide relates to Guide 02:** the motherboard (control board), the drivers and the sensors are **already mounted and wired** as described in [Guide 02](02_electronics.md). This guide does not repeat the wiring. It starts from the point where the machine is electrically validated and explains the **Klipper configuration of the motherboard** and of the rest of the machine.

**Purpose of this document:** to explain the content that will be published in this guide once the project's assembly documentation is available. Firmware versions, exact menus, command lines and machine parameters will be specified in the final version of the booklet.

### Objectives

- Present the software chain of the CeleauPrinter 10 and the role of each building block.
- Explain the procedure for installing, updating and backing up the firmware.
- Define the **Klipper configuration of the motherboard**: motion system, steps per millimetre, reference position, sensors, heaters and the machine-specific options.
- Describe the use of the tools for preparing print files and slicing profiles.
- Provide a diagnostic method that can be used as soon as the first anomaly appears.

## Prerequisites — check points before you start

Before opening this booklet, validate the following points:

- [ ] The **electrical** part has been validated and [Guide 02](02_electronics.md) closed without anomaly.
- [ ] The **hardware configuration** (axes, sensors, actuators, homing) is known and matches the assembled machine.
- [ ] A computer with the **communication port and the network** required by the machine is available.
- [ ] The **software tools** indicated by the project (control interface, slicer, utilities) are installed in their intended version.
- [ ] The official **firmware and configuration files** for the project version have been retrieved.
- [ ] A **backup of the existing configuration** has been made before any update or modification.
- [ ] The machine is on a **stable support**, the travels are clear and the emergency stop is accessible.

## Plan of the booklet

The final version will be organised into the following chapters, in this order:

1. **Overview of the software chain** — from the microcontroller to the control station: components, exchanges and role of each building block.
2. **Installing and updating the firmware** — flashing procedure, compatible versions, post-install checks and the rollback strategy.
3. **Configuring Klipper and the motherboard** — the `printer.cfg` structure, motion system definition, steps per millimetre, endstops and homing, heaters, fans and the machine-specific options.
4. **Software calibration** — homing, tool offset adjustment and the other software-driven calibrations.
5. **Preparing print files** — slicer profile, start and end G-code, adaptation to the machine's particularities.
6. **Print queues and sequences** — organisation of batches and chained prints, when the project provides a dedicated tool for this use.
7. **Control and monitoring** — connection to the control station, state visualisation, sending and following a print.
8. **Diagnostics, logs and backups** — reading the logs, analysing common errors, exporting and restoring configurations.

## Out of scope for this document

To avoid any confusion while reading:

- The **wiring diagrams** and the connector references, covered in [Guide 02 — Electronics](02_electronics.md).
- The **exact configuration values**, which depend on the hardware version and will be supplied with the final documentation.
- The **mechanical assembly**, covered in [Guide 01 — Mechanics](01_mechanics.md).
- The **first print procedure**, covered in [Guide 04 — First print and operation](04_first_print_ops.md).

## Safety and good practices

- Never **interrupt a flash** or unplug the cable during a transfer: plan for a stable power supply for the whole operation.
- Keep a **backup copy** of the firmware and of the configuration before any update.
- Check the **provenance of downloaded files** and refrain from modifying undocumented parameters.
- Test any modification on a **stopped machine**, without a part, before using it for a real print.

## Related resources

- [Main project README](../README.md) — overview, versions and safety.
- [Guide 01 — Mechanics](01_mechanics.md) — structure and mechanical assembly.
- [Guide 02 — Electronics](02_electronics.md) — power supply, wiring and first power-up.
- [Guide 04 — First print and operation](04_first_print_ops.md) — calibration and first print.

## Navigation

| ← Previous | Next → |
| :--- | :--- |
| [Guide 02 — Electronics](02_electronics.md) | [Guide 04 — First print and operation](04_first_print_ops.md) |

[Back to the main README](../README.md)
