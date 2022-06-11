# opencore-efi
Config files for my Hackintosh setup on ASUS X540YA-XO033D.   
Works with macOS Catalina 10.15.7. Untested with Big Sur, probably would be PITA to run. Monterey is confirmed to be not working.   
**OpenCore version**: 0.8.0
## What works
 - Boot
 - Battery Indicator (partial)
 - Ethernet/WiFi
 - Touchpad (partial)
 - USB ports (partial)
## What doesn't work
 - USB3/Type-C ports
 - Bluetooth
 - iGPU (will never work cuz APU)
 - AirPort
 - Touchpad gestures
 - Battery status change
 - Audio
## What **probably** works
 - Power management
 - Sleep
 - OTA update to Big Sur, not sure though, it won't let me to update to Big Sur
## Hardware
--------------------------
| Component | Model      |
|-----------|------------|
| Laptop    |X540YA-XO033D|
| CPU       | E1-7010    |
| iGPU      | Radeon R2  |
| Sound Card| CX20752    |
| WiFi Card | QCA9565    |
| Eth Card  | RTL8136    |
--------------------------
