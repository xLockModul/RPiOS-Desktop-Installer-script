# Desktop Environment Installer for Raspberry Pi

This script simplifies the process of installing and setting up desktop environments on Raspberry Pi devices. It provides a user-friendly interface that allows you to select from a variety of desktop environments, including Xfce4, Cinnamon, LXQt, MATE, GNOME Shell, KDE Plasma, Budgie, Deepin, Enlightenment, LXDE, Pantheon, and Trinity Desktop Environment.

**Recommended Operating System**

This script is specifically designed to work with Raspberry Pi OS Lite 64-bit or 32-bit for optimal performance. However, it can also be used on Raspberry Pi OS with the standard desktop (PIXEL) or on other Debian-based Linux distros for Raspberry Pi to replace the existing desktop environment with the selected one.

**Replacing the Existing Desktop**

If you are using Raspberry Pi OS with the standard desktop (PIXEL), you can use this script to replace it with the selected desktop environment. To do this, simply follow the on-screen instructions to select the desired desktop environment, and then the script will automatically remove and replace the existing desktop.

Please note that some desktop environments may not be as well-tested as others on Raspberry Pi, so you may experience some bugs. It is also recommended to back up your Raspberry Pi before using this script, in case you need to revert to the original desktop environment.

## Installation

1. Download the `desktop-installer.sh` script to your Raspberry Pi using `wget`.

```bash
wget https://raw.githubusercontent.com/xLockModul/RPiOS-Desktop-Installer-script/main/desktop-installer.sh
```

2. Make the script executable.

```bash
chmod +x desktop-installer.sh
```

3. Run the script directly using the following command:

```bash
./desktop-installer.sh
```

4. Follow the on-screen instructions to select the desired desktop environment and set it as the default.

5. Once the installation is complete, the Raspberry Pi will restart and the selected desktop environment will be loaded.

## Features

* User-friendly interface with arrow key navigation and Enter key selection
* Supports a variety of desktop environments
* Automatic repository installation for the selected desktop environment
* Sets the selected desktop environment as the default
* Restarts the Raspberry Pi after installation

## Notes

* Some desktop environments may not be as well-tested as others on Raspberry Pi, so you may experience some bugs.
* Please proceed with caution when installing the Deepin desktop environment, as it is not officially maintained for Raspberry Pi.
* You can use this script to replace the existing desktop environment on Raspberry Pi OS with the standard desktop (PIXEL).
* Please back up your Raspberry Pi before using this script.

## License

This project is licensed under the MIT License.
