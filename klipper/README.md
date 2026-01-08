# KlipperPi

## System Information

- SBC: OrangePi Zero 3 @ 1 GB RAM
- OS: Debian Bookworm OrangePi Image
- Printer: Ender 3 V3 SE @ Klipper firmware

## Klipper Installation

Klipper installed with the [KIAUH](https://github.com/dw-0/kiauh) script.
Installed Klipper, Moonraker and Mainsail.
Created Klipper firmware (klipper.bin).
> Run `make menuconfig` in Klipper directory.
> Selected processor model `STM32F103`.
> Selected `28 KiB` bootloader.
> Selected Communication Interface `Serial on USART1 (PA10/PA9)`.
> Saved configuration and run `make`.
Copy/Moved the klipper.bin file to formatted SD Card.
Restart printer with SD Card inserted to run the new firmware.

## KAMP Installation

Installed KAMP with the [guide](https://github.com/kyleisah/Klipper-Adaptive-Meshing-Purging) in GitHub.

## Klipper Configuration

Klipper configuration files are in `./config/`, see each for more information.
Needs to have all in need to start the printer.

To run the printer/klipper without KAMP, comment `[include KAMP_Settings.cfg]` in the `printer.cfg` file (line 10).
