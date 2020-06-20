elims_housekeeping
=================
Housekeeping Library for various Arduino Variants. 

* Simple Serial UI to provide WiFi provisioning, settings dialoges and status messages.
* Stores global settings permanently in flash.
* Abstraction layer for communication interfaces.
* Latching push button power circuit control with auto-off after time-out.

## Compatibility
Arduino                   | WiFi         | BLE         | MQTT       | Modbus TCP  | Notes
------------------------- | :----------: | :---------: | :--------: | :---------: | -----
Adafruit Feather M0 WiFi  |      X       |             |      X     |             |
Arduino Nano 33 IoT       |      X       |             |      X     |             |
Arduino MKR1010 WiFi      |      X       |             |      X     |             |
Arduino MKR1000 WiFi      |      X       |             |      X     |             |
