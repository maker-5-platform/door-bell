# Door bell: parts

The parts of the design, by name and count. Where they come from and what
they cost is not part of the design. Written by the Maker-5 edge.

## Hardware

| Part | Kind | Count | To buy |
|---|---|---|---|
| 12 V → 5 V 3 A step-down | electronic | 1 | yes |
| 16 GB card, Raspberry Pi OS Lite 32-bit bookworm | electronic | 1 |  |
| 4-in-1 converter AHD/TVI/CVI/CVBS → HDMI | electronic | 1 | yes |
| 4-wire intercom cable, AWG24, up to 15 m | electronic | 1 |  |
| Coupling capacitor + LM386 amplifier board | electronic | 1 | yes |
| DIN-rail supply TMEZON Modulo DR-60-12 | electronic | 1 |  |
| Ethernet cable to the door, or a Linux-friendly USB Wi-Fi stick | electronic | 1 | yes |
| Logic-level MOSFET or small relay on GPIO 27 | electronic | 1 | yes |
| Monitor MZ-IP-V142B | electronic | 1 |  |
| Optocoupler PC817 + resistors | electronic | 1 | yes |
| Outdoor door station | electronic | 1 |  |
| Powered USB hub | electronic | 1 | yes |
| Raspberry Pi 1 Model B | electronic | 1 |  |
| Small perfboard, terminal blocks, enclosure | mechanical | 1 | yes |
| Spare Android phone, Samsung Galaxy A50 | electronic | 1 |  |
| The lock | electronic | 1 |  |
| USB HDMI grabber | electronic | 1 | yes |
| USB sound card | electronic | 1 | yes |

## Software

| Module | Version | Runs on |
|---|---|---|
| alsa-utils (aplay) | 1.2.8 | Raspberry Pi 1 Model B |
| Chrome (Android 11) |  | Spare Android phone, Samsung Galaxy A50 |
| Config | /etc/dhc-door/config.json | Raspberry Pi 1 Model B |
| dhc-door adapter (index.js) | devops edge stage | Raspberry Pi 1 Model B |
| Edge web app, Codes and Door bell pages |  |  |
| espeak-ng | 1.51 | Raspberry Pi 1 Model B |
| ffmpeg | 5.1.9 | Raspberry Pi 1 Model B |
| gpiod (gpiomon) | 1.6.3 | Raspberry Pi 1 Model B |
| Hue bridge / Homematic CCU (optional) |  |  |
| Mosquitto with Dynamic Security |  |  |
| mqtt (npm) | 5.16.1 | Raspberry Pi 1 Model B |
| Node-RED with the dhc-panel palette (engine, broker rules) |  |  |
| Node.js | 18.20.4 | Raspberry Pi 1 Model B |
| Phone page /app/panel/ (panel.js, tinymqtt.js) |  |  |
| Raspberry Pi OS Lite 32-bit (Debian 12 bookworm) | kernel 6.12.109 (rpi-v6) | Raspberry Pi 1 Model B |
| Settings: Stay awake while charging, lock type swipe or none on a dedicated phone |  | Spare Android phone, Samsung Galaxy A50 |
