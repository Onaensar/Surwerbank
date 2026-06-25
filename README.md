# Surwerbank
# Hybrid Powerbank: Solar + MagSafe + 18W Fast Charge 

Welcome to the **Hybrid Survivor Powerbank** repository! This project is a fully open-source, high-efficiency power management board designed for ultimate portability and outdoor resilience. 

Unlike standard powerbanks, this board integrates **18W Bidirectional Fast Charging**, **MPPT Solar Energy Harvesting**, and **MagSafe Compatible Wireless Charging** into a single, compact PCB.

**Designed by:** Abdullah Ensar 
**Institution:** İzmir Bakırçay University, Electrical and Electronics Engineering

---

## ✨ Key Features & Core ICs

### 1. ⚡ 18W Fast Charging & Power Management (IP5328P)
At the heart of the board is the **IP5328P** SoC, handling high-efficiency bi-directional charging. 
* Supports multiple fast-charge protocols (QC3.0, PD, AFC, FCP).
* Stable 5A output capability for demanding devices.
* Deeply filtered power delivery with strategic capacitor placement (low ripple).

### 2. ☀️ MPPT Solar Harvesting (CN3791)
Built for off-grid scenarios, the board includes a dedicated **CN3791** Maximum Power Point Tracking (MPPT) circuit.
* Connect a compatible solar panel to the terminal block.
* Extracts maximum available power from the sun to trickle-charge the lithium cells, significantly extending standby and active use time in outdoor environments.

### 3. 🧲 Wireless & MagSafe Charging (IP6808)
No cables? No problem. The **IP6808** wireless charging transmitter ensures your devices stay powered up seamlessly.
* Optimized resonance capacitor array for stable Tx transmission.
* Designed to be highly compatible with MagSafe form factors.

### 4. 🛡️ Rugged & Enclosure-Ready Mechanical Design
This PCB isn't just an electrical prototype; it is designed for real-world mechanical integration.
* **Mounting Holes:** M3 mounting holes placed at the corners for secure installation inside 3D printed or waterproof enclosures.
* **Optimized Clearances:** Type-C receptacle (J2) is perfectly aligned with the board edge (Edge.Cuts) to ensure flush mounting and cable compatibility.
* *Note: The mechanical STEP file is included for easy integration into Fusion 360 / SolidWorks to design custom rugged cases.*

---

## 🛠️ Fabrication & Assembly (Gerber Files)
The board has passed all DRC checks with 0 Errors and 0 Warnings in KiCad. 
* **Layer Count:** 2 Layers
* **Copper Weight:** 1 oz (recommended) or 2 oz for enhanced thermal dissipation under 5A loads.
* **Polygons:** Generous Top and Bottom GND pours with extensive via stitching for thermal relief and low impedance.

You can find the production-ready `.zip` file containing all Gerber and Drill files in the `Fabrication` folder.

## 📄 License
This project is released under the **Open Source Hardware (OSHW)** license. Feel free to use, modify, and build upon this design!
