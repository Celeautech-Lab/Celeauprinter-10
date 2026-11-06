## Bill of Materials (BOM)

This bill of materials lists each item using its **CAD Tree Reference** and **Standard Designation** exactly as supplied in the cleaned BOM. The CAD reference is the label used in the project CAD tree; the designation is the component or procurement name to use when identifying the part. Quantities are the total required for one machine.

> **Important Note — Licensing and fabrication:** All items marked `ORIGINAL_FILE_LICENSE` are standard off-the-shelf components that can be sourced online and remain subject to the licenses of their original files. Only items marked `CELEAUTECH` are custom parts to be fabricated by the builder from the project files. Do not treat the CELEAUTECH parts as purchased COTS components.

### Custom-part materials

All custom `CELEAUTECH` 3D-printed parts are designed to be printed in **ASA** for thermal and mechanical resistance, except the four `FOOT` parts. Print `FOOT` (quantity 4) in **TPU 64D** (recommended) or **TPU 95A**, using sufficient infill to damp vibrations.

> **Important Note — 3 mm planar-part alternative:** Several flat, 3 mm structural/mechanical parts designed to be printed in ASA were initially considered for laser cutting in acrylic (PMMA); that option was discarded because of brittleness under vibration and screw-clamping loads. Standard CO2 laser cutting in **3 mm POM-C (Acetal / Delrin)**, or in **High-Impact Acrylic**, is a viable mechanical and thermal alternative to ASA printing. Celeautech has **not tested** the POM-C laser-cutting option. Feedback and contributions from builders who test it are very welcome. Confirm each part’s geometry and fit before substituting a cut part for a printed one.

### Filament handling and 5 kg spools

There is intentionally **no spool holder in this BOM**. The printer is designed for serial production using large 5 kg industrial spools. To maintain consistent print quality across an entire 5 kg spool, use an external, large-capacity active filament dryer equipped with a pneumatic fitting output. Connect that output directly to the extruder/filament-sensor inlet using a PTFE tube. The recommended option is the **Creality Multi-kilo Filament Dryer**, compatible with 5 kg spools.

---

## 1. Fasteners — Screws

| INDEX | CAD_REFERENCE | DESIGNATION | Qty | Specifications / notes |
| ---: | --- | --- | :---: | --- |
| 1 | `CHC_M4X6` | **SOCKET_HEAD_SCREW_M4X6** | 80 | Standard off-the-shelf component. |
| 2 | `CHC_M4X10` | **SOCKET_HEAD_SCREW_M4X10** | 70 | Standard off-the-shelf component. |
| 3 | `CHC_M3X8` | **SOCKET_HEAD_SCREW_M3X8** | 46 | Standard off-the-shelf component. |
| 4 | `CHC_M4X16` | **SOCKET_HEAD_SCREW_M4X16** | 40 | Standard off-the-shelf component. |
| 5 | `CHC_M3X16` | **SOCKET_HEAD_SCREW_M3X16** | 22 | Standard off-the-shelf component. |
| 6 | `CHC_M3X10` | **SOCKET_HEAD_SCREW_M3X10** | 16 | Standard off-the-shelf component. |
| 7 | `CHC_M4X8` | **SOCKET_HEAD_SCREW_M4X8** | 16 | Standard off-the-shelf component. |
| 8 | `CHC_M5X12` | **SOCKET_HEAD_SCREW_M5X12** | 16 | Standard off-the-shelf component. |
| 9 | `CHC_M3X20` | **SOCKET_HEAD_SCREW_M3X20** | 14 | Standard off-the-shelf component. |
| 10 | `CHC_M3X12` | **SOCKET_HEAD_SCREW_M3X12** | 11 | Standard off-the-shelf component. |
| 11 | `M4X30_FLUSH_HEAD_SCREW` | **FLUSH_HEAD_SCREW_M4X30** | 4 | Standard off-the-shelf component. |
| 12 | `CHC_M2_5X20` | **SOCKET_HEAD_SCREW_M2_5X20** | 4 | Standard off-the-shelf component. |
| 13 | `CHC_M3X25` | **SOCKET_HEAD_SCREW_M3X25** | 4 | Standard off-the-shelf component. |
| 14 | `CHC_M5X45` | **SOCKET_HEAD_SCREW_M5X45** | 4 | Standard off-the-shelf component. |
| 15 | `CHC_M3X50` | **SOCKET_HEAD_SCREW_M3X50** | 3 | Standard off-the-shelf component. |
| 16 | `CHC_M3X6` | **SOCKET_HEAD_SCREW_M3X6** | 2 | Standard off-the-shelf component. |
| 17 | `CHC_M4X30` | **SOCKET_HEAD_SCREW_M4X30** | 2 | Standard off-the-shelf component. |
| 18 | `CHC_M5X30` | **SOCKET_HEAD_SCREW_M5X30** | 2 | Standard off-the-shelf component. |
| 19 | `CHC_M5X40` | **SOCKET_HEAD_SCREW_M5X40** | 2 | Standard off-the-shelf component. |

---

## 2. Fasteners — Nuts, Spacers and Washers

| INDEX | CAD_REFERENCE | DESIGNATION | Qty | Specifications / notes |
| ---: | --- | --- | :---: | --- |
| 20 | `M4_T-SLOT_NUT` | **M4_T_SLOT_NUT** | 185 | Standard off-the-shelf component. |
| 21 | `M3_T-SLOT_NUT` | **M3_T_SLOT_NUT** | 24 | Standard off-the-shelf component. |
| 22 | `SPACER_M3X6X5` | **SPACER_M3X6X5** | 24 | Standard off-the-shelf component. |
| 23 | `ECROU_HM3` | **THIN_HEX_NUT_M3** | 24 | Standard off-the-shelf component. |
| 24 | `ECROU_H3` | **HEX_NUT_M3** | 22 | Standard off-the-shelf component. |
| 25 | `M5_T-SLOT_NUT` | **M5_T_SLOT_NUT** | 16 | Standard off-the-shelf component. |
| 26 | `ECROU_H4` | **HEX_NUT_M4** | 14 | Standard off-the-shelf component. |
| 27 | `M4_WASHER` | **M4_WASHER** | 12 | Standard off-the-shelf component. |
| 28 | `A311A00500` | **NYLOCK_NUT_M5** | 8 | Standard off-the-shelf component. |
| 29 | `ECROU_H5` | **HEX_NUT_M5** | 6 | Standard off-the-shelf component. |
| 30 | `ECROU_H2_5` | **HEX_NUT_M2_5** | 4 | Standard off-the-shelf component. |
| 31 | `SPACER_M2X5X5` | **SPACER_M2X5X5** | 4 | Standard off-the-shelf component. |

---

## 3. Brackets

| INDEX | CAD_REFERENCE | DESIGNATION | Qty | Specifications / notes |
| ---: | --- | --- | :---: | --- |
| 32 | `ANGLE_BRACKET_2020` | **ANGLE_BRACKET_2020** | 36 | Standard off-the-shelf component. |
| 33 | `SLICK_ANGLE_BRACKET_2020` | **SLICK_ANGLE_BRACKET_2020** | 4 | Use standard off-the-shelf brackets and file them on one side. |

---

## 4. Aluminum Profiles

| INDEX | CAD_REFERENCE | DESIGNATION | Qty | Specifications / notes |
| ---: | --- | --- | :---: | --- |
| 34 | `2020_PROFILE_300` | **2020_PROFILE_300** | 4 | Standard off-the-shelf component. |
| 35 | `2020_PROFILE_550` | **2020_PROFILE_550** | 4 | Standard off-the-shelf component. |
| 36 | `2040_PROFILE_450` | **2040_PROFILE_450** | 4 | Standard off-the-shelf component. |
| 37 | `2040_PROFILE_L350` | **2040_PROFILE_L350** | 3 | Standard off-the-shelf component. |
| 38 | `2020_PROFILE_L250` | **2020_PROFILE_L250** | 2 | Standard off-the-shelf component. |
| 39 | `2020_PROFILE_L400` | **2020_PROFILE_L400** | 2 | Standard off-the-shelf component. |
| 40 | `2040_PROFILE_L300` | **2040_PROFILE_L300** | 2 | Standard off-the-shelf component. |
| 41 | `2040_PROFILE_L400` | **2040_PROFILE_L400** | 2 | Standard off-the-shelf component. |

---

## 5. Linear Motion

| INDEX | CAD_REFERENCE | DESIGNATION | Qty | Specifications / notes |
| ---: | --- | --- | :---: | --- |
| 42 | `SK16` | **LINEAR_SHAFT_SUPPORT_SK16** | 8 | Standard off-the-shelf component. |
| 43 | `LM162837UU` | **LINEAR_BALL_BUSHING_LM16UU** | 4 | Standard off-the-shelf component. |
| 44 | `Z_AXIS_RAIL` | **Z_AXIS_LINEAR_SHAFT_16MM** | 4 | Standard off-the-shelf component. |
| 45 | `MGN12H` | **LINEAR_GUIDE_CARRIAGE_MGN12H** | 3 | Standard off-the-shelf component. |
| 46 | `MGN12H_350MM` | **LINEAR_GUIDE_RAIL_MGN12_350MM** | 3 | Standard off-the-shelf component. |
| 47 | `TR08` | **TRAPEZOIDAL_LEAD_SCREW_NUT_TR8** | 2 | Standard off-the-shelf component. |
| 48 | `TRAPEZOIDAL_SCREW` | **TRAPEZOIDAL_LEAD_SCREW_TR8** | 2 | Standard off-the-shelf component. |

---

## 6. Transmission

| INDEX | CAD_REFERENCE | DESIGNATION | Qty | Specifications / notes |
| ---: | --- | --- | :---: | --- |
| 49 | `GT2_20T` | **GT2_PULLEY_20T** | 8 | Standard off-the-shelf component. |
| 50 | `NATV5PP_5X16X12` | **YOKE_TRACK_ROLLER_BEARING_5X16X12** | 4 | Standard off-the-shelf component. |
| 51 | `CXJH-C-D25-D5-E5` | **FLEXIBLE_SHAFT_COUPLER_5X5MM_D25** | 2 | Standard off-the-shelf component. |
| 52 | `GT2_16T` | **GT2_PULLEY_16T** | 2 | Standard off-the-shelf component. |
| 53 | `40T_GT2_PULLEY_10MM_5MM` | **40T_GT2_PULLEY_10MM_5MM** | 1 | Standard off-the-shelf component. |
| 54 | `GT2_PULLEY_20T_10MM_5MM` | **GT2_PULLEY_20T_10MM_5MM** | 1 | Standard off-the-shelf component. |

---

## 7. Electronics and Motors

| INDEX | CAD_REFERENCE | DESIGNATION | Qty | Specifications / notes |
| ---: | --- | --- | :---: | --- |
| 55 | `40-42_MOTOR` | **NEMA17_STEPPER_MOTOR_42X40** | 6 | Standard off-the-shelf component. |
| 56 | `OPTICAL_ENDSTOP_SWITCH` | **OPTICAL_ENDSTOP_SWITCH** | 4 | Standard off-the-shelf component. |
| 57 | `MOSFET` | **MOSFET** | 2 | Standard off-the-shelf component. |
| 58 | `25X25X10_FAN (VALOR PREDETERMINADO)` | **25X25X10_FAN** | 1 | Standard off-the-shelf component. |
| 59 | `BIGTREETECH_OCTOPUS_V1_0` | **BIGTREETECH_OCTOPUS_V1_0** | 1 | Standard off-the-shelf component. |
| 60 | `BIGTREETECH_PI_V1_2` | **BIGTREETECH_PI_V1_2** | 1 | Standard off-the-shelf component. |
| 61 | `BLTOUCH_V3-1_ASM` | **BLTOUCH_V3_1** | 1 | Standard off-the-shelf component. |
| 62 | `BTT_RELAY_V1_2` | **BTT_RELAY_V1_2** | 1 | Standard off-the-shelf component. |
| 63 | `SFS_V2_0_MODEL` | **BTT_SFS_V2_0** | 1 | Standard off-the-shelf component. |
| 64 | `EMERGENCY-START_BUTTON` | **EMERGENCY_STOP_BUTTON** | 1 | Standard off-the-shelf component. |
| 65 | `HOT_BED` | **HOT_BED** | 1 | Standard off-the-shelf component. |
| 66 | `LRS-600_N2_` | **MEANWELL_LRS_600_PSU** | 1 | Standard off-the-shelf component. |
| 67 | `POWER_SWITCH` | **POWER_SWITCH** | 1 | Standard off-the-shelf component. |
| 68 | `RADIAL-COOLING-FAN-5015-DC12V (ПО УМОЛЧАНИЮ)` | **RADIAL_COOLING_FAN_5015_DC12V** | 1 | Standard off-the-shelf component. |

---

## 8. Extrusion System

| INDEX | CAD_REFERENCE | DESIGNATION | Qty | Specifications / notes |
| ---: | --- | --- | :---: | --- |
| 69 | `PNEUMATIC_COUPLING_PC4-M6` | **PNEUMATIC_COUPLING_PC4_M6** | 2 | Standard off-the-shelf component. |
| 70 | `BMG EXTRUDER ALL METALL (STANDARD)` | **BMG_EXTRUDER_ALL_METAL** | 1 | Standard off-the-shelf component. |
| 71 | `ACOPLADOR DA VENTOINHA (VALOR PREDETERMINADO)` | **FAN_DUCT** | 1 | Standard off-the-shelf component. |
| 72 | `TUBO CONECTOR (VALOR PREDETERMINADO)` | **HEATBREAK_TUBE** | 1 | Standard off-the-shelf component. |
| 73 | `BLOCO AQUECEDOR (VALOR PREDETERMINADO)` | **HEATER_BLOCK** | 1 | Standard off-the-shelf component. |
| 74 | `DISSIPADOR (VALOR PREDETERMINADO)` | **HEATSINK** | 1 | Standard off-the-shelf component. |
| 75 | `HOTEND` | **HOTEND** | 1 | Standard off-the-shelf component. |
| 76 | `BICO 0.4MM (VALOR PREDETERMINADO)` | **NOZZLE_0_4MM** | 1 | Standard off-the-shelf component. |

---

## 9. Custom Fabricated Parts — Belt Bed System

CELEAUTECH custom parts: fabricate from the project files; print in ASA unless the specific material exception below applies.

| INDEX | CAD_REFERENCE | DESIGNATION | Qty | Specifications / notes |
| ---: | --- | --- | :---: | --- |
| 77 | `BED-SUPPORT` | **BED_SUPPORT** | 4 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 78 | `BED_SUPPORT_SPACER` | **BED_SUPPORT_SPACER** | 4 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 79 | `CONE_ROLL` | **CONE_ROLL** | 4 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 80 | `CONE_ROLL_STOPPER` | **CONE_ROLL_STOPPER** | 4 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 81 | `BED_MOTOR_SUPPORT` | **BED_MOTOR_SUPPORT** | 1 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 82 | `BELT_ENDSTOP_SUPPORT_1` | **BELT_ENDSTOP_SUPPORT_1** | 1 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 83 | `BELT_ENDSTOP_SUPPORT_2` | **BELT_ENDSTOP_SUPPORT_2** | 1 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 84 | `LEFT_FRONT_BELT_BEARING_SUPPORT` | **LEFT_FRONT_BELT_BEARING_SUPPORT** | 1 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 85 | `LEFT_REAR_BELT_BEARING_SUPPORT` | **LEFT_REAR_BELT_BEARING_SUPPORT** | 1 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 86 | `RIGHT_FRONT_BELT_BEARING_SUPPOR` | **RIGHT_FRONT_BELT_BEARING_SUPPORT** | 1 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 87 | `RIGHT_REAR_BELT_BEARING_SUPPORT` | **RIGHT_REAR_BELT_BEARING_SUPPORT** | 1 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |

---

## 10. Custom Fabricated Parts — Z Axis and Frame

CELEAUTECH custom parts: fabricate from the project files; print in ASA unless the specific material exception below applies.

| INDEX | CAD_REFERENCE | DESIGNATION | Qty | Specifications / notes |
| ---: | --- | --- | :---: | --- |
| 88 | `FOOT` | **FOOT** | 4 | Custom CELEAUTECH part; print in TPU 64D (recommended) or TPU 95A with sufficient infill for vibration damping. |
| 89 | `Z_BEARING_LOCKER` | **Z_BEARING_LOCKER** | 4 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 90 | `Z_BEARING_SUPPORT_BIS` | **Z_BEARING_SUPPORT_BIS** | 4 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 91 | `Z_AXIS_MOTOR_SUPPORT` | **Z_AXIS_MOTOR_SUPPORT** | 2 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 92 | `Z_NUT_SUPPORT` | **Z_NUT_SUPPORT** | 2 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 93 | `ELECTRONICS_PANEL` | **ELECTRONICS_PANEL** | 1 | CELEAUTECH custom panel; laser-cut in MDF or adapt for laser/CNC cutting in aluminum sheet. |
| 94 | `POWER_SUPPLY_CARTER` | **POWER_SUPPLY_COVER** | 1 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 95 | `Z_ENDSTOP_SUPPORT` | **Z_ENDSTOP_SUPPORT** | 1 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 96 | `Z_MAX_FLAG` | **Z_MAX_FLAG** | 1 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 97 | `Z_MAX_SENSOR_SUPPORT` | **Z_MAX_SENSOR_SUPPORT** | 1 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |

---

## 11. Custom Fabricated Parts — XY Floating Frame

CELEAUTECH custom parts: fabricate from the project files; print in ASA unless the specific material exception below applies.

| INDEX | CAD_REFERENCE | DESIGNATION | Qty | Specifications / notes |
| ---: | --- | --- | :---: | --- |
| 98 | `FLOATING_FRAME_PULLEY_SUPPORT` | **FLOATING_FRAME_PULLEY_SUPPORT** | 2 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 99 | `XY_BELT_LOCKER` | **XY_BELT_LOCKER** | 2 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 100 | `XY_MOTOR_SUPPORT` | **XY_MOTOR_SUPPORT** | 2 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 101 | `X_AXIS_SUPPORT` | **X_AXIS_SUPPORT** | 2 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 102 | `X_PULLEYS_SUPPORT` | **X_PULLEYS_SUPPORT** | 2 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 103 | `X_ENDSTOP_SUPPORT` | **X_ENDSTOP_SUPPORT** | 1 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 104 | `X_FLAG` | **X_FLAG** | 1 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 105 | `Y_FLAG` | **Y_FLAG** | 1 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |

---

## 12. Custom Fabricated Parts — Print Head

CELEAUTECH custom parts: fabricate from the project files; print in ASA.

| INDEX | CAD_REFERENCE | DESIGNATION | Qty | Specifications / notes |
| ---: | --- | --- | :---: | --- |
| 106 | `BLTOUCH_SUPPORT` | **BLTOUCH_SUPPORT** | 1 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 107 | `HEAD_PLATE` | **HEAD_PLATE** | 1 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |
| 108 | `NOZZLE_FAN_SUPPORT` | **NOZZLE_FAN_SUPPORT** | 1 | Custom CELEAUTECH 3D-printed part; print in ASA for thermal and mechanical resistance. |

---
