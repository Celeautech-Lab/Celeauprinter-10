# Guide 02 — Electronics

**CeleauPrinter 10 — Power supply, wiring, sensors and first power-up**

> **Status:** content plan. The full version of this guide will be published together with the project's assembly documentation. This file describes what the guide will cover; it does not yet contain a step-by-step procedure.

---

## About this guide

This booklet covers the **electronics** part of the CeleauPrinter 10: the power architecture, the connections between the control computer, the peripherals and the actuators, and the checks to perform before the first power-up. It is written for the person who wires, connects and verifies the electrical part of the machine.

**How this guide relates to Guide 01:** the electronic components — control board, power supply, drivers, sensors, motors — are treated here as **parts that have already been mounted** during the mechanical assembly of [Guide 01](01_mechanics.md). Guide 01 explains how they are fitted and secured; this guide takes over from there and explains how they are **wired**. No mechanical mounting procedure is repeated here.

**Purpose of this document:** to explain the content that will be published in this guide once the project's assembly documentation is available. The wiring diagrams, connector references, polarities and detailed test sequences will be added in the final version; they are not reproduced here.

### Objectives

- Present the electrical architecture of the machine and the role of each functional block.
- Explain the power distribution, protection and grounding logic of the machine.
- Define the wiring rules (power, signal, ground, sleeving) that will be applied in the final version.
- Prepare the safety checks and the measurements to perform before the first power-up.
- Provide the basis for the electrical validation that gates the rest of the journey.

## Prerequisites — check points before you start

Before opening this booklet, validate the following points:

- [ ] The **mechanical** part has been assembled and the mechanical review of [Guide 01](01_mechanics.md) is validated.
- [ ] The **wiring diagram** and the electronic nomenclature for your version are available.
- [ ] The **electronic components** have been verified (reference, condition, polarity) before any connection.
- [ ] A working **multimeter** is available for continuity, polarity and short-circuit measurements.
- [ ] The **cables, connectors and sleeving** match the diameters and lengths required by the wiring diagram.
- [ ] The machine is **disconnected from any power supply** while wiring, and the workspace is clear.
- [ ] You know where the **power cut-off** points are and how to reach them quickly.

## Plan of the booklet

The final version will be organised into the following chapters, in this order:

1. **Overview of the electrical architecture** — functional blocks of the machine, power hierarchy, general flow of energy and signals.
2. **Electronic nomenclature** — mapping of the components, their references and their role in the machine.
3. **Power supply and distribution** — organisation of the power sources, circuit protection and the cabling requirements for power.
4. **Power and signal wiring** — wiring conventions, sleeving, terminal blocks, connections of actuators and peripherals.
5. **Sensors and position detection** — connecting the sensors, endstop wiring and reference detection.
6. **Actuators and control** — the link between the control computer, the drivers and the motors, including grounding.
7. **Electrical safety** — isolation, protections, earth bonding and management of the risks linked to the power supply.
8. **Checks before the first power-up** — no-load verification sequence, continuity and short-circuit measurements, then controlled test runs.

## Out of scope for this document

To avoid any confusion while reading:

- The **detailed wiring diagrams** and the wire identification, which will accompany the project documentation.
- The **mechanical mounting** of the cable supports and pass-throughs, covered in [Guide 01 — Mechanics](01_mechanics.md).
- The **firmware settings** and machine commands, covered in [Guide 03 — Software](03_software.md).
- The **first print procedure**, covered in [Guide 04 — First print and operation](04_first_print_ops.md).

## Safety and good practices

- Keep the machine **unpowered** throughout the wiring and checking phase.
- Check **polarity and continuity** before the first start: an inverted polarity can damage a component.
- Never work on the **mains supply circuit** without the appropriate training and equipment; call on a qualified third party if necessary.
- Keep an **accessible cut-off means** during tests and maintain a **safe distance** around the moving parts.
- Insulate **bare conductors** and make sure that no wire rubs, is pinched or enters a moving mechanism.

## Related resources

- [Main project README](../README.md) — overview, nomenclature and safety.
- [Guide 01 — Mechanics](01_mechanics.md) — structure and mechanical assembly.
- [Guide 03 — Software](03_software.md) — firmware and machine configuration.
- [Guide 04 — First print and operation](04_first_print_ops.md) — calibration and first print.

## Navigation

| ← Previous | Next → |
| :--- | :--- |
| [Guide 01 — Mechanics](01_mechanics.md) | [Guide 03 — Software](03_software.md) |

[Back to the main README](../README.md)
