# NUT USB UPS Configurator

A script to detect and configure Network UPS Tools (NUT) for USB-connected UPS devices on Linux systems, ensuring safe and automated shutdown procedures.

## Features

- **Detect USB UPS Devices**: Uses `lsusb` to detect USB UPS devices from common manufacturers like Tripp Lite, APC, CyberPower, and Eaton.
- **Configure NUT**: Installs and configures NUT for the detected USB UPS devices.
- **Set Battery Threshold**: Prompts the user to set the battery percentage for initiating shutdown.
- **Clear Existing Configurations**: Option to clear existing NUT configurations.
- **Check Service Status**: Option to check the status of NUT services after configuration.
- **Logging**: Logs actions and outputs to `/var/log/nut_setup.log`.

## Usage

1. **Download the Script**:

   ```sh
   wget https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/nut-usb-ups-configurator/main/setup_nut_with_dynamic_shutdown.sh
