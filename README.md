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

<img width="1600" height="945" alt="image" src="https://github.com/user-attachments/assets/83bb4c3a-d9a4-4ede-9157-42b93a1caecd" />


### 2. Network Server – Recent Events

<img width="1600" height="928" alt="image" src="https://github.com/user-attachments/assets/0c2b7732-195b-44ff-a81d-3a7afe86803e" />


### 4. Relay Status Dashboard Output

### Door Open → Relay ON  

<img width="1600" height="940" alt="image" src="https://github.com/user-attachments/assets/e155cc8a-35a9-44ff-a8e3-c25385c8d8c7" />

### Door Open → Relay OFF

<img width="1600" height="939" alt="image" src="https://github.com/user-attachments/assets/9a188ba6-25b1-4206-bb09-e0c220733c64" />

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
