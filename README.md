# Heavy-Duty Tracked Dolly 🚜

<img width="2483" height="1803" alt="IMG_0396" src="https://github.com/user-attachments/assets/4e895d89-f4a8-4f91-8607-bdd579638bf7" />

An ESP32-controlled, high-torque tracked dolly designed for heavy agricultural automation and load transport. Capable of pulling loads exceeding 500kg, this dolly is built to handle rough terrain and streamline tasks like feeding, seeding, and manure management.

## 🌟 Features
* **Massive Towing Capacity:** Geared and tracked to pull 500kg+ loads effortlessly.
* **Wireless Control:** Fully teleoperated using a reliable HotRC DS-600 remote control.
* **Custom Powerhouse:** Powered by a scratch-built 48V 30Ah LiFePO4 battery pack engineered for sustained high-current delivery.
* **Modular Design:** Built to accept various agricultural attachments for multi-purpose farm use.

## ⚙️ Hardware & Electronics
The control system translates standard RC signals into smooth motor control using an ESP32 and a DAC.

* **Microcontroller:** ESP32 (programmed via Arduino IDE)
* **Transmitter/Receiver:** HotRC DS-600 (6-channel RC system)
* **DAC:** MCP4725 (Translates ESP32 digital signals into smooth analog voltages for the motor controllers)
* **Drive System:** Heavy-duty tracked undercarriage with high-torque electric motors.

## 🔋 Power System
The dolly is powered by a custom-built, heavy-duty battery pack along with dual 48v 750w BLDC motors designed specifically for this platform's power requirements.

* **Configuration:** 48V 30Ah
* **Chemistry & Layout:** 32140 LiFePO4 cells in a 15s2p configuration.
* **Construction:** Hand-built using pure nickel strips and spot-welded for minimal resistance and safe, high-current draw.

## 🛠️ Current Applications
Right now, the dolly is actively used on the farm for:

1. **Manure Management:** Transporting and dumping manure efficiently.
2. **Feed Transport:** Hauling heavy loads of cattle feed.
3. **Seeding:** Operating with a custom seeding machine attachment for automated planting.

## 🚀 Future Roadmap
The platform is continually evolving. Planned attachments and upgrades include:
- [ ] **Screw Conveyor Attachment:** For automated, hands-free manure collection.
- [ ] **Belt Conveyor Attachment:** To automate the movement and distribution of silage.
