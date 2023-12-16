# Desktop Environment Installer for Raspberry Pi

This script simplifies the process of installing and setting up desktop environments on Raspberry Pi devices. It provides a user-friendly interface that allows you to select from a variety of desktop environments, including Xfce4, Cinnamon, LXQt, MATE, GNOME Shell, KDE Plasma, Budgie, Deepin, Enlightenment, LXDE, Pantheon, and Trinity Desktop Environment.

**Recommended Operating System**

This script is specifically designed to work with Raspberry Pi OS Lite 64-bit or 32-bit for optimal performance. However, it can also be used on Raspberry Pi OS with the standard desktop (PIXEL) or on other Debian-based Linux distros for Raspberry Pi to replace the existing desktop environment with the selected one.

**Using the Script on Other Debian-based Linux Distros**

The script should work on other Debian-based Linux distros for Raspberry Pi, but your mileage may vary. It has been tested on Raspbian and Ubuntu MATE, but it may not work perfectly on all distros. It is also recommended to back up your Raspberry Pi before using this script, in case you need to revert to the original desktop environment.

## Installation

1. **Check if curl is installed:**

```bash
command -v curl
```

If curl is installed, this command will print the path to the curl executable.

2. **Install curl if it is not installed:**

```bash
sudo apt install curl
```

3. **Download the `desktop-installer.sh` script to your Raspberry Pi using curl:**

```bash
curl https://github.com/xLockModul/RPiOS-Desktop-Installer-script/blob/a4661ac4ed8673318e9304d6ab894209ca618d8f/desktop-installer.sh > desktop-installer.sh
```

4. **Make the script executable:**

```bash
chmod +x desktop-installer.sh
```

5. **Run the script directly using the following command:**

```bash
./desktop-installer.sh
```

6. **Follow the on-screen instructions to select the desired desktop environment and set it as the default.**

7. **Once the installation is complete, the Raspberry Pi will restart and the selected desktop environment will be loaded.**

## Features

* User-friendly interface with arrow key navigation and Enter key selection
* Supports a variety of desktop environments
* Automatic repository installation for the selected desktop environment
* Sets the selected desktop environment as the default
* Restarts the Raspberry Pi after installation

## Notes

* Some desktop environments may not be as well-tested as others on Raspberry Pi, so you may experience some bugs.
* **Please proceed with caution when installing the Deepin desktop environment, as it is not officially maintained for Raspberry Pi.**
* You can use this script to replace the existing desktop environment on Raspberry Pi OS with the standard desktop (PIXEL).
* Please back up your Raspberry Pi before using this script.

## License

This project is licensed under the MIT License.
