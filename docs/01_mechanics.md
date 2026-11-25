# Guide 01 — Mechanics

**CeleauPrinter 10 — Structure, sub-assemblies and mechanical assembly**

> **Status:** Complete (Assembly Sequence & Critical Points). Intended for experienced makers and engineers. Refer to the repository's STEP/CAD files and the BOM for exact fastener sizes, part references, and detailed geometry.

---

## About this guide

This booklet covers the **mechanical assembly** of the CeleauPrinter 10: build order, critical integration steps, and mechanical checks before power-up.

**Target audience:** Experienced makers. Rather than a screw-by-screw tutorial, this guide focuses on the **correct assembly sequence** (to avoid painting yourself into a corner) and key mechanical tolerances. Keep the **3D CAD / STEP assembly** open alongside this document and rely on it for all exact part orientations and fastener details.

### Key Specifications
- **Build Volume:** `230 × 230 × 250 mm` (X/Y footprint based on a standard Ender 3 bed).
- **Kinematics:** Flying CoreXY Z-gantry on linear guides and leadscrews.
- **Extrusion:** All-metal BMG dual-drive + Volcano-style hotend (70 W heater).
- **Bed:** Continuous conveyor belt bed *(Note: mechanical assembly is documented here, but continuous printing operation is still pending validation)*.

---

## Prerequisites — check points before you start

Before starting the build, validate the following points:

- [ ] The **main README** and **BOM** have been reviewed.
- [ ] The **STEP / STL / 3MF** files matching your hardware are open in your CAD viewer.
- [ ] Printed parts have been **removed from supports**, deburred, and visually inspected for cracks or dimensional issues.
- [ ] All fasteners, linear guides, leadscrews, and extrusions are sorted and measured.
- [ ] The workstation is **flat, stable, and protected** (essential for squaring the main frame).

---

## Assembly Sequence

Follow this exact order to avoid having to disassemble sub-assemblies later. **For every step below, refer to the CAD/STEP assembly for exact fastener sizes, part orientations, and mounting locations.**

### 1. Flying CoreXY Z-Gantry
Assemble the flying gantry as an independent sub-assembly first (refer to the CAD for bracket orientation and belt routing):
- Build the CoreXY frame, corner brackets, and XY motor mounts.
- Install the linear guides/carriages and the **BMG dual-drive + Volcano** toolhead carriage.
- Route and lightly tension the CoreXY belts (leave final fine-tuning for step 5).
- **Check:** Verify that the XY carriage moves smoothly across the full `230 × 230 mm` travel without binding.

![Flying CoreXY Z-Gantry CAD](../images/cad_flying_gantry.png)

### 2. Conveyor Belt Bed Assembly
> **Note:** The conveyor belt mechanism is mechanically assembled at this stage, though its long-term continuous operation has not yet been validated under print loads.

Refer to the CAD for roller spacing, bearing seats, and bracket placement:
- Assemble the bed frame, drive/idler rollers, and belt tensioning mounts.
- Install the continuous conveyor belt around the rollers.
- **Check:** Ensure the rollers are parallel to each other and apply light, even tension so the belt tracks straight without drifting to either side when rotated by hand.

### 3. Main Chassis & Gantry Integration
**Critical step — do not fully close the frame before inserting the flying gantry.** Refer to the CAD for extrusion lengths, gusset positions, and linear guide alignment:
- Assemble the base and vertical extrusions of the main chassis on a flat reference surface, checking for squareness.

![Main Chassis Ready for Gantry](../images/cad_chassis_open.png)

- **Insert the Flying CoreXY Z-gantry** onto the vertical linear guides and **thread it onto the Z trapezoidal leadscrews** *before* locking the top frame members in place.
- Install the conveyor belt bed sub-assembly into the main chassis.
- Secure the top frame extrusions and perform a final squareness check on the entire structure.

![Completed Main Chassis with Gantry](../images/cad_chassis_complete.png)

### 4. Electronics Mounting Plates & Boards
Refer to the CAD for mounting plate placement and board hole patterns:
- Mount the electronics support plates onto the main chassis.
- Fasten the mainboards, power supply, and **BTT SFS V2.0** filament runout/motion sensor (positioned along the path from the 5 kg spool holder to the extruder).
- **Note:** Keep wiring disconnected during this step; electrical connections are covered in [Guide 02 — Electronics](02_electronics.md).

![Complete Printer — Electronics Plate POV](../images/cad_electronics_pov.png)

### 5. Final Mechanical Review (Before Power-Up)
- **PTFE & Filament Path:** Cut and route the PTFE tube cleanly from the 5 kg spool feed / SFS V2.0 sensor to the BMG extruder, avoiding sharp bends (check CAD clearances).
- **Belt Tension:** Finalize CoreXY belt tension (equal tension on both A/B belts) and Z-axis alignment.
- **Travel & Clearances:** Manually move X, Y, and Z across the full `230 × 230 × 250 mm` envelope. Verify there are no collisions with the frame, electronics plates, or conveyor rollers.
- **Fasteners:** Double-check all structural screws, pulley grub screws, and leadscrew couplers.

---

## Out of scope for this document

- **Screw-by-screw CAD references** (refer directly to the STEP assembly).
- **Wiring diagrams and pinouts** → [Guide 02 — Electronics](02_electronics.md).
- **Firmware configuration (Klipper/Marlin)** → [Guide 03 — Software](03_software.md).
- **Conveyor belt calibration & first print tuning** → [Guide 04 — First print and operation](04_first_print_ops.md).

---

## Safety and good practices

- **Never power on** the machine until the mechanical review (Step 5) is completely validated.
- Never force a binding screw or linear carriage; binding indicates a misalignment or frame squareness issue.
- Keep tools, metal shavings, and loose screws away from belts, leadscrews, and electronics boards.

---

## Related resources

- [Main project README](../README.md) — overview, nomenclature and safety.
- [Guide 02 — Electronics](02_electronics.md) — wiring and first power-up.
- [Guide 03 — Software](03_software.md) — firmware and machine configuration.
- [Guide 04 — First print and operation](04_first_print_ops.md) — calibration and first print.

## Navigation

| ← Previous | Next → |
| :--- | :--- |
| [Main README](../README.md) | [Guide 02 — Electronics](02_electronics.md) |

[Back to the main README](../README.md)
