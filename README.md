# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server
## Aim
To configure a LoRaWAN end device and monitor IR sensor data using a network server and dashboard visualization.

## Components Required
- LoRaWAN End Device-STM32
- LoRaWAN Gateway
- Application Server Dashboard
- Serial Port Utility
- Development Tools (STM32CubeIDE, STM32CubeProgrammer)

## Procedure
1. Open STM32CubeIDE and import the project from the realy-control project directory.
2. Select the LoRaWAN End Node project for the NUCLEO-WLE5JC board.
3. Clean all previous build files using the Clean Project option in the build configuration.
4. Build the project to generate the firmware files.
5. Flash the compiled firmware into the STM32 board using STM32CubeProgrammer with baud rate set to 9600.
6. Open the network server console and login using your registered email ID and password.
7. Register the device by selecting Device Types and adding the LoRaWAN device in the network server.
8. Open the Serial Port Utility  give the AT commands and verify device connection through the serial port utility
9. Create a dashboard on the application server by clicking the Add Dashboard option.
10. Add widgets and commands to visualize the relay status data.
11. Send control commands from the dashboard to control the relay.

## Output
### 1. Serial Port Utility – Network Server Connection

<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/10a07266-3101-40fc-8af3-6f739b022f42" />


### 2. Network Server – Recent Events

<img width="1600" height="777" alt="image" src="https://github.com/user-attachments/assets/74dd1c49-a8e3-4585-9a1f-d92326e3ec74" />

### 3. Dashboard Command Sending

<img width="1914" height="970" alt="Screenshot 2026-03-19 022928" src="https://github.com/user-attachments/assets/ab9ce9fd-28b0-4107-8265-8bbf273d9af0" />


### 4. Relay Status Dashboard Output

### Bulb ON → Relay ON  

<img width="1919" height="1020" alt="Screenshot 2026-03-18 144207" src="https://github.com/user-attachments/assets/c0d4726e-a536-4844-a6b0-5175a6806ea6" />

### Bulb OFF → Relay OFF

<img width="1918" height="1012" alt="Screenshot 2026-03-18 145233" src="https://github.com/user-attachments/assets/4bb898fa-251e-4e4f-bf2f-80fd69c0db43" />

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
