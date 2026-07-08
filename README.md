# Smart Home Automation Controller (4-Channel Relay)

This project is a compact and integrated **Smart Home Automation Controller** designed using KiCad. It allows users to control household appliances remotely via Wi-Fi, leveraging the power of the ESP32-WROOM-32E module.

## 🚀 Key Features
* **Microcontroller:** ESP32-WROOM-32E (Integrated Wi-Fi & Bluetooth connectivity).
* **Power Management:**
    * Integrated AC-to-DC converter (230V AC to 5V DC).
    * High-efficiency 5V to 3.3V step-down regulator for stable power supply to the ESP32.
* **Control Unit:** 4-Channel Relay board to switch high-voltage home appliances (lights, fans, etc.).
* **Design:** Compact, single-board design suitable for wall-mount enclosures.
* **Flexibility:** The board is designed to be modular, allowing users to adapt inputs/switches based on specific smart home requirements.

## 🛠 Technical Specifications
* **Controller:** ESP32-WROOM-32E
* **Relay Channels:** 4 x High-quality relays with opto-isolation (for safety).
* **PCB Layers:** 2-Layer Board (FR4 material).
* **Design Software:** KiCad EDA.

## ⚠️ Safety Warning
This project involves dealing with **230V AC Mains voltage**. Please ensure all high-voltage connections are properly insulated and handled with extreme caution during testing and installation.

## 📂 Project Structure
* `/Schematic` - Contains the circuit design and architecture.
* `/PCB` - Contains the PCB layout (.kicad_pcb file).
* `/Gerbers` - Contains the manufacturing files (Gerber & Drill files) for PCB fabrication.

---
*Designed for home automation enthusiasts and IoT developers.*
