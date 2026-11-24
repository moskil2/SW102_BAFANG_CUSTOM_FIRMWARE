# Third-party components

The SW102 firmware application is © 2026 Tomasz Pieczara, all rights reserved (see `LICENSE`). The release files contain the following third-party components, each under its own license.

## Bluetooth update package (`SW102_BAF_FW_X.Y.Z.zip`)

Contains only the firmware application. The application is built with parts of:

- **Nordic Semiconductor nRF5 SDK 12.3.0** - © Nordic Semiconductor ASA, under the Nordic Semiconductor license included in the SDK (binary redistribution permitted for use with Nordic Semiconductor devices).
- **newlib (nano)** C library - under the BSD-style licenses of its authors.

## Full flash image (`SW102_BAF_X.Y.Z.hex`)

In addition to the application above, the full image contains:

- **Nordic Semiconductor S130 SoftDevice 2.0.1** (Bluetooth stack) - © Nordic Semiconductor ASA, under the Nordic Semiconductor license distributed with it, unmodified.
- **SW102 DFU bootloader** - from the OpenSourceEBike project, licensed under GPL-3.0. Its source code is available at https://github.com/OpenSourceEBike/SW102_LCD_Bluetooth-bootloader. The bootloader is a separate program and is included unmodified.
