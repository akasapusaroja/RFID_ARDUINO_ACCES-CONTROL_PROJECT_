# RFID_ARDUINO_ACCES-CONTROL_PROJECT_
This project implements a secure RFID-based door access control system using Arduino UNO and the MFRC522 RFID module. It verifies authorized RFID cards and controls a door lock, LED indicators, and buzzer for real-time feedback. The system also includes a manual push button to simulate emergency access or door override.
  ⚙️ Features

✅ Grants or denies access based on registered RFID card UID.

🔒 Controls an electronic lock mechanism (or simulated lock pin).

💡 Green/Red LEDs indicate access granted or denied.

🔊 Buzzer feedback for system alerts.

🔁 Manual button for emergency or authorized manual entry.

🧩 Components

Arduino UNO

MFRC522 RFID Reader

RFID Cards/Tags

LEDs (Green & Red)

Buzzer

Push Button

Relay or lock simulation output

🧠 Working Principle

When an RFID tag is scanned, the system checks if the UID matches the authorized ID (83 23 38 BB by default).

If matched → green LED glows, buzzer beeps, and the lock opens for 3 seconds.

If not matched → red LED flashes with buzzer alert.

The push button can also unlock the system manually.

🛠️ Libraries Required

SPI.h

MFRC522.h

🚀 Future Enhancements

Add GSM or Wi-Fi for logging access remotely.

Include LCD or OLED display for messages.

Store multiple authorized UIDs in EEPROM.
