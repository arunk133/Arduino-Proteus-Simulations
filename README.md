# Arduino & Proteus Hardware Simulation Workspace

This repository features a collection of integrated hardware layouts, circuit designs, and project configurations. It provides the physical wiring schematics, component paths, and visual testing environments built using **Proteus Design Suite** and **Keil uVision**.

### 🔗 Companion Software Repository
> 💡 **Looking for the code?** The programmatic firmware logic that drives these hardware layouts is hosted in the companion repository:  
> 👉 **[Arduino-Embedded-Firmware](https://github.com/arunk133/Arduino-Embedded-Firmware)** 

---

## 📂 Repository Contents

* **🔌 Circuit Schematic Diagrams (`.pdsprj`)** `NEW CIRCUIT FILE.pdsprj`, `switch.pdsprj`, `7 led.pdsprj`, `single led.pdsprj` — Virtual hardware breadboards containing wired microcontroller pin configurations, power rails, pull-up resistors, and device peripherals. These files simulate the physical electronics before they are built.
  
* **🏗️ IDE Workspaces (`.uvproj`)** `PROJECT2.uvproj`, `led.uvproj`, `led2.uvproj`, `switch.uvproj` — Keil uVision project configuration setups. These manage internal compiler definitions, chip selection options, and build targets for the microcontrollers used in the schematics.

---

## 🛠️ Software Requirements

To load, modify, and interact with these circuit models, you will need the following engineering tools:
1. **Proteus Design Suite** (Required to run the live, interactive visual circuit simulations and test inputs)
2. **Keil uVision IDE** (Optional — used to manage workspace target compilation parameters)
