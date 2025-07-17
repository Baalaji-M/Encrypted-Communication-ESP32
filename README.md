Encrypted Communication: Secure ESP32-to-ESP32 Data Transfer
Overview
This project implements secure communication between two ESP32 microcontrollers using the ESP-NOW protocol. It focuses on sending structured data (e.g., integer values) wirelessly with features like packet acknowledgment and error handling. The system is designed for data integrity in wireless sensor networks, with provisions for AES encryption to prevent unauthorized access.

Note: The provided code demonstrates basic ESP-NOW functionality without explicit AES encryption. To add encryption, integrate a library like AESLib or Arduino's Crypto library. Encrypt the data struct before sending and decrypt on receipt. If you have the encrypted code, update the files accordingly.

Features:
Wireless peer-to-peer communication between ESP32 devices.
Structured data transmission (e.g., custom structs with integers).
Callback functions for send/receive status and error handling.
Support for adding AES encryption for secure data transfer.
Low-latency, suitable for real-time applications like IoT or robotics.

Hardware Requirements:
Two ESP32 development boards (e.g., ESP32-WROOM-32).
USB cables for programming and serial monitoring.
(Optional) Serial monitor tool like Arduino IDE for debugging.

Software Requirements:
Arduino IDE (version 2.0+ recommended).
ESP32 board support installed via Arduino Board Manager.

Libraries:
ESP32 core (built-in with board support).
(For encryption) AESLib or similar (install via Library Manager).
