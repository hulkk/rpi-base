# rpi-base
An ansible role to configure base settings for a Raspberry Pi.

## Requirements
- Raspberry Pi Zero 2 W, 4 or 5
- write Raspberry Pi OS Lite (64-bit) to microSD using Raspberry Pi Imager with following changes to OS customisation settings
    - General
        - [x] Set username and password
        - [x] configure wireless lan (optional)
    - Services
        - [x] enable ssh
        - [x] Allow public-key authentication only
    - Options
        - [ ] enable telemetry
- insert the microSD card to the Raspberry Pi
- connect via SSH using configured username and ssh key
