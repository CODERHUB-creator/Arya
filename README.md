# EV Charging Station Management System (Java)

A runnable console-based college project based on the uploaded project report. It demonstrates vehicle registration, charger availability, slot allocation, charging sessions, meter validation, billing, and completed-session history.

## Requirements
- JDK 17 or newer
- Visual Studio Code
- VS Code Extension Pack for Java (recommended)

## Open in VS Code
1. Extract `EV_Charging_Station_Java.zip`.
2. In VS Code choose **File → Open Folder** and select `EV_Charging_Station_Java`.
3. Open the integrated terminal (**Terminal → New Terminal**).
4. Compile:
   ```bash
   javac -d out src/*.java
   ```
5. Run:
   ```bash
   java -cp out Main
   ```

On Windows PowerShell, these commands work as written when run from the project folder.

## How to use
1. Register a vehicle (option 1).
2. View chargers (option 2).
3. Start a session (option 3), enter the registration number, choose AC or DC Fast, and enter the initial meter reading.
4. Finish the session (option 4), enter the session ID and final meter reading.
5. View the bill and session history (options 4 and 5).

## Sample tariff
- AC: ₹10/kWh
- DC Fast: ₹12/kWh

These are illustrative academic values, not live commercial prices.

## Scope and limitations
This is a console prototype. It uses in-memory collections, so records reset when the program exits. Meter readings are simulated; it does not connect to physical chargers, a live database, maps, or payment gateways.
