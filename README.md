# Two-Stage Spur Gear Reducer Gearbox (SolidWorks)

**A complete 3D CAD assembly** of a two-stage spur gear speed reducer modeled in **SolidWorks** (MMGS units, ANSI Metric gear standard). The assembly includes 13 unique native `.SLDPRT` components (21 total instances), concentric shaft mates, mechanical gear mates (`17:56` and `18:73`), and a floating left casing for axial disassembly and internal inspection.

## Technical Specifications

| Parameter | Specification |
| :--- | :--- |
| **Gear Standard** | ANSI Metric, Involute Spur Gears |
| **Module (m)** | 2.0 mm |
| **Pressure Angle (α)** | 20° |
| **Face Width** | 15.0 mm (all gears) |
| **Stage 1 Reduction (Gear A → Gear B)** | 17T → 56T (`3.29:1`, Center Distance: `73.0 mm`) |
| **Stage 2 Reduction (Gear C → Gear D)** | 18T → 73T (`4.06:1`, Center Distance: `91.0 mm`) |
| **Overall Reduction Ratio** | **13.36 : 1** |
| **Unit System** | MMGS (Millimeter, Gram, Second) |
| **Total Components** | 13 unique parts (21 instances in assembly) |

## Bill of Materials (BOM)

| Part No. | Component Name | Qty | Key Dimensions (mm) |
| :---: | :--- | :---: | :--- |
| 1 | Gearbox Right Side Casing | 1 | `282.7 × 178.2 × 38.0` (Base, fixed) |
| 2 | Gearbox Left Side Casing | 1 | `282.7 × 178.2 × 38.0` (Mirrored + Ø27 input bore) |
| 3 | 3rd Gear Shaft Stopper Tube | 1 | OD Ø30 × ID Ø20 × 4 |
| 4 | Cosmetic Bearing (Output) | 2 | OD Ø47 × ID Ø25 × 12 |
| 5 | Cosmetic Bearing (Input / Intermediate) | 4 | OD Ø42 × ID Ø20 × 12 |
| 6 | Output Shaft | 1 | Ø25×68, Ø35×4 collar, Ø30×15 (25 mm flat), L = 87 |
| 7 | Output Shaft Stopper Tube | 1 | OD Ø35 × ID Ø25 × 21 |
| 8 | Retaining Ring (Snap Ring) 20 mm | 4 | ID Ø20 / OD Ø25 × 1 |
| 9 | Retaining Ring (Snap Ring) 25 mm | 2 | ID Ø25 / OD Ø30 × 1 |
| 10 | Gear D (Output Gear) | 1 | 73T, Pitch Ø146, Ø30/25 flat bore, 6×Ø30 & 6×Ø10 holes |
| 11 | Gear C (Intermediate Gear-Shaft) | 1 | 18T, Pitch Ø36, stepped shafts + 20 mm flat seat, L = 62 |
| 12 | Gear B (Intermediate Gear) | 1 | 56T, Pitch Ø112, Ø25/20 flat bore, 7×Ø20 & 7×Ø8 holes |
| 13 | Gear A (Input Pinion Shaft) | 1 | 17T, Pitch Ø34, Ø19×100 keyed shaft (75×4 keyway), L = 162 |

## How to Open & Inspect

1. Clone or download this repository into a single local folder (keep all `.SLDPRT` files in the same directory as the `.SLDASM` file).
2. Open `Two_Stage_Reducer_Gearbox_Assembly.SLDASM` in **SolidWorks**.
3. **Disassemble / Inspect:** The right casing is fixed as the base; drag the **Left Side Casing** straight out along its concentric guide axis to open the housing, or slide any shaft, gear, or bearing along its axis.
4. **Motion Study:** Rotate the input shaft (**Gear A**) or apply a rotary motor (e.g., 50 RPM) to observe the `13.36:1` two-stage speed reduction.

## Reference

- Modeled following the [Two Stage Reducer Gearbox Parts and Assembly in SolidWorks](https://www.youtube.com/watch?v=TY2BL-nJ6Z0) tutorial (CAD CAM TUTORIAL BY MAHTABALAM).

## License

This project is shared for educational and CAD portfolio purposes under the MIT License.
