# SIM7600 Pi HAT

This is a custom Raspberry Pi HAT (Hardware Attached on Top) designed using the SIM7600 module. It enables LTE cellular communication, GPS positioning, and SMS capabilities, making it ideal for IoT projects, remote telemetry, and mobile data applications.

## 📡 Key Features

- **SIM7600 4G Module**
  - LTE CAT1 or CAT4 support (depending on variant)
  - GPS/GLONASS positioning
  - SMS send/receive support
- **Compatible with Raspberry Pi GPIO Header (40-pin)**
- **Supports USB and UART communication**
- **Optional Power Management Circuit**
- **Onboard SIM card slot and antenna connectors**

## 🛠️ Project Details

- Designed with **KiCAD**
- Follows Raspberry Pi HAT mechanical specs
- Optimized for **low power operation**
- Easily integrates into IoT and M2M deployments

## 🧰 Files Included

- `.kicad_pro`, `.kicad_pcb`, `.kicad_sch` – main KiCAD design files
- `3DModels/` – STEP/VRML models for enclosure design (if any)
- `BOM/` – Bill of Materials (CSV or PDF)
- `README.md` – project description

## ⚙️ Getting Started

1. Flash your Raspberry Pi with Raspbian OS.
2. Insert SIM card and connect LTE/GPS antennas.
3. Use UART or USB (AT commands) to interface with SIM7600.
4. Optional: Use `minicom`, `PPP`, or `pyserial` for testing.

## 🔗 References

- [SIMCom SIM7600 Datasheet](https://www.simcom.com/product/SIM7600.html)
- [Raspberry Pi HAT Specs](https://github.com/raspberrypi/hats)

## 📜 License

This project is open-source under the MIT License.
