# First PCB – Two-LED Board (Hack Club Highway)

This is my first-ever PCB. It’s a simple two-LED circuit designed as part of Hack Club’s [Highway](https://highway.hackclub.com/) tutorial. I used KiCAD for the schematic and PCB layout.

---

## 🧠 Notes

- This board lights up two LEDs. That’s it.
- Designed entirely from scratch following the Hack Club tutorial.

---

## 🗂 Files

- `.kicad_pro`, `.sch`, `.kicad_pcb` – project files
- `/gerbers/` – contains the manufacturing ZIP
- `/assets/` – schematic, PCB layout, and 3D render screenshots

---

## 📦 Bill of Materials (BOM)

| Quantity | Part               | Footprint                                      | Notes                       |
|----------|--------------------|------------------------------------------------|-----------------------------|
| 2        | LED (5mm)          | `LED_D5.0mm`                                   | Standard through-hole LEDs |
| 2        | Resistor (220Ω)    | `R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal` | Current limiting           |
| 1        | Battery Holder     | `BatteryHolder_Keystone_3034_1x20mm`           | For CR2032 coin cell       |

> If you're ordering components, double-check tolerances, lead pitch, and power ratings.

---

## 📸 Screenshots

- `assets/schematic.png`
- `assets/pcb.png`
- `assets/render.png`

---

## 🧑 Slack Username

Hack Club Slack: `@Nullskulls`

---

## Credits

Built as part of Hack Club's Highway program  
Tutorial: [https://highway.hackclub.com/](https://highway.hackclub.com/)
