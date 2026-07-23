MIYIO - Smart Assistive Watch for the Visually Impaired

A compact wearable smartwatch designed to improve independence and safety for visually impaired users through vibration-based time notification, fall detection, and emergency SOS functionality.

Overview

MIYIO is a Final Year Project that combines embedded systems, wearable technology, and assistive technology into a compact smartwatch. Instead of relying on a screen or speaker, the watch communicates through vibration patterns, making it suitable for users with visual impairments.

Features
🕒 Vibration-based time notification
🚨 Automatic fall detection
🆘 SOS emergency button
📱 Bluetooth Low Energy (BLE) connectivity
🔋 Rechargeable Li-Po battery
⏰ High-accuracy DS3231M Real-Time Clock
📳 Mini vibration motor feedback
🎛 Three tactile control buttons
Hardware
Component	Model
Microcontroller	ESP32-C3 SuperMini
Accelerometer	GY-521 (MPU6050)
RTC	DS3231M
Charging IC	TP4056-42
Voltage Regulator	AP2112K-3.3V
Transistor	2N2222
Diode	1N5819
Battery	3.7V Li-Po
Feedback	Coin Vibration Motor
Software
Arduino IDE
KiCad 9
ESP32 Arduino Framework
Repository Structure
MIYIO/
├── Firmware/          # Arduino source code
├── PCB/               # KiCad schematic & PCB
├── 3D_Model/          # Watch enclosure
├── Images/            # Project images
├── Documents/         # Report & documentation
└── README.md
Current Progress
✅ Hardware selection
✅ Circuit schematic
✅ PCB layout
🔄 PCB routing
⏳ 3D enclosure
⏳ Firmware development
⏳ Prototype assembly
⏳ Testing & validation
Future Improvements
Mobile companion application
GPS location tracking
Wireless charging
Heart rate monitoring
Improved battery life
Authors

Dan
Final Year Project

License

This project is intended for educational and research purposes.

This README is concise, looks good on GitHub, and follows the style commonly used in open-source hardware projects.
