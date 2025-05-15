# Gps-using-neom9n-
      Compact GPS breakout board based on the u-blox NEO-M9N module. Includes support circuitry for battery-backed operation, LEDs, and passives—designed for low-power embedded GPS applications.

# GPS_M Module – Compact GPS Breakout Board

> Compact GPS breakout board based on the **u-blox NEO-M9N** module. Includes support circuitry for battery-backed operation, LEDs, and passives—designed for low-power embedded GPS applications.

---

## 📦 Files Included

- `GPS_m_gerber/`: Full set of Gerber files for PCB manufacturing.
- `neom9n.csv`: Bill of Materials (BOM) with part references, values, and footprints.

## 🧩 Overview

- **GPS Chip:** u-blox NEO-M9N
- **Power Source:** Designed for coin cell MS621T-FL11E
- **Form Factor:** Compact dual-layer board
- **Ideal For:** GPS logging, time synchronization, compact embedded systems

## 🔩 Components Overview

| Reference     | Value                   | Footprint               | Quantity |
|---------------|-------------------------|--------------------------|----------|
| B1            | 6.8MM Coin Cell         | MS621T-FL11E             | 1        |
| C1            | 47pF Capacitor          | GRM1885C1H470JA01D       | 1        |
| C3–C6         | 1uF Capacitors          | GRM21BR61C105KA01L       | 4        |
| CR1           | 1N4148WX-TP Diode       | CR_SOD323_MCC            | 1        |
| D1, D4        | LEDs                    | WL-SMCW_0603             | 2        |
| ...           | *(See full BOM file)*   |                          |          |

> 💡 For the full list of components, refer to `neom9n.csv`.

## 🛠️ How to Use

1. **Order the PCB** using the Gerber files in the `GPS_m_gerber/` folder.
2. **Order parts** based on the BOM file `neom9n.csv`.
3. **Assemble the board** using standard SMD soldering practices.

## 📎 License

This hardware design is released under the [CERN-OHL-W v2](https://ohwr.org/project/cernohl/wikis/home) open hardware license.
