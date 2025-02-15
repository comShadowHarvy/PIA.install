# PIA.install

Script to install and configure OpenVPN with PIA in a container.

## Features

- Installs OpenVPN and necessary utilities.
- Downloads and extracts PIA configuration files.
- Creates a secure credentials file for PIA.
- Modifies the .ovpn file to use the absolute path of the credentials file.
- Provides an optional startup script example.

## Configuration

Before running the install script, update the following in PIA.sh:
- PIA_USERNAME: Change to your actual Private Internet Access username.
- PIA_PASSWORD: Change to your actual Private Internet Access password.
- DEFAULT_PIA_CONFIG_FILE: Update to a different server config if desired.

## Usage

1. Make the install script executable:
   ```bash
   chmod +x PIA.sh
   ```

2. Run the script:
   ```bash
   ./PIA.sh
   ```

## Credits

Developed by ShadowHarvy
