# RFID-based-door-Lock-System-on-Blynk-app
I developed an RFID-based door lock system using the ESP8266 microcontroller. This project integrates an RFID reader to authenticate users and control the door lock mechanism. The system uses the Blynk app for real-time monitoring and saving entry logs. 
I created an RFID-based door lock system that uses the ESP8266 microcontroller to enhance security and convenience. The system leverages RFID technology for user authentication and the Blynk app for real-time monitoring and logging of entries.
Components Used

    ESP8266 Microcontroller: The core of the system, handling communication between the RFID reader and the Blynk app.
    RFID Reader and Tags: Used to authenticate users. Each tag has a unique ID that the system reads and verifies.
    Solenoid Lock: Controlled by the ESP8266, it locks and unlocks the door based on RFID authentication.
    Blynk App: An IoT platform that saves entry logs and provides a user interface for monitoring the system.

Features

    User Authentication:
        The RFID reader scans the RFID tags.
        The ESP8266 verifies if the scanned tag is registered.
        If authenticated, the solenoid lock is activated to unlock the door.

    Real-Time Monitoring and Logging:
        The Blynk app saves the entry logs, including timestamps and tag details.
        Users can monitor the door status and view entry logs through the Blynk app.

    Security:
        Only registered RFID tags can unlock the door.
        Unauthorized attempts are logged for security audits.

Implementation

    Hardware Setup:
        Connect the RFID reader to the ESP8266.
        Connect the solenoid lock to a relay module controlled by the ESP8266.
        Power the system using a suitable power supply.

    Software Development:
        Program the ESP8266 using the Arduino IDE.
        Implement the RFID reading and verification logic.
        Integrate the Blynk library to handle communication with the Blynk app.
        Write code to log entries in the Blynk app and control the solenoid lock.

    Blynk App Configuration:
        Create a Blynk project and configure widgets to display entry logs and door status.
        Connect the Blynk project to the ESP8266 using authentication tokens.
