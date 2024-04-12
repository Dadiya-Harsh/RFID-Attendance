# RFID Attendance 

RFID Attendance  is an Arduino-based project that allows you to track attendance using RFID technology and a NodeMCU (ESP8266) microcontroller. This system can be used in various environments such as schools, offices, or events to automate attendance tracking.

## Features

- Supports RFID card scanning for attendance tracking.
- Connects to a local Wi-Fi network for data transmission.
- Sends attendance data to a designated server for storage and processing.
- Provides real-time feedback through serial communication.

## Requirements

- Arduino IDE for programming the NodeMCU microcontroller.
- MFRC522 library for RFID functionality.
- ESP8266WiFi library for Wi-Fi connectivity.
- ESP8266HTTPClient library for sending HTTP requests.
- A compatible RFID reader module.
- Access to a local Wi-Fi network.
- A server for receiving and processing attendance data.

## Installation

1. Clone or download the project files to your local machine.
2. Open the `NodeMCU_RFIDv2.0.ino` file in the Arduino IDE.
3. Install the required libraries mentioned in the `libraries` section of the code.
4. Customize the Wi-Fi SSID, password, server URL, and device token variables to match your setup.
5. Upload the code to your NodeMCU board.

## Usage

1. Power on the NodeMCU board and ensure it is connected to the Wi-Fi network.
2. Hold an RFID card near the RFID reader module.
3. The system will detect the card, send its UID to the server, and receive a response.
4. The server processes the data and may respond with feedback such as "login," "logout," "successful," or "available."
5. View the serial monitor for real-time feedback and debugging.

## Troubleshooting

- If encountering compilation errors, ensure that all required libraries are properly installed in the Arduino IDE.
- Verify that the Wi-Fi credentials and server URL in the code are correct.
- Check the serial monitor for error messages and debug information.

## Contributing

Contributions to the project are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.
