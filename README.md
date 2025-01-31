# My Ubuntu CLI Commands and Used Packages

This repository contains a list of essential **Ubuntu commands** and commonly used **package installations** that I use to manage and enhance my Ubuntu system. These commands and packages cover system updates, development tools, browser extensions, and more.

---

## Ubuntu Commands

These are some of the basic commands to keep your Ubuntu system up-to-date and healthy.

### Update Package List

This command fetches the latest package information from all repositories configured on your system. It updates the local package database, ensuring your system is aware of the latest available packages and their versions.

```sh
sudo apt update
```

### Upgrade Installed Packages

This command upgrades all currently installed packages to their newest versions available in the configured repositories. It's important to run `sudo apt update` first to ensure the package list is up-to-date. This command will not remove packages, but it may install new dependencies if required by the newer versions.

```sh
sudo apt upgrade
```

### Reboot System

This command initiates a system reboot. It's often necessary after installing updates, especially kernel updates, to ensure the changes take effect. Be sure to save your work before running this command.

```sh
sudo reboot
```

## How to Shut Down Ubuntu Using the Command Line

You can safely shut down your Ubuntu system using the following commands:

### 1️⃣ Immediate Shutdown

To power off the system immediately, run:

```sh
sudo shutdown -h now
```

<!-- -------------------------------------------------------------- -->

## Ubuntu install pkg

These are some of package for my Ubuntu system.

## Installing Google Chrome on Ubuntu

To install Google Chrome on Ubuntu using the `.deb` package, follow these steps:

1. Download the latest Google Chrome `.deb` package from [Google Chrome's official website](https://www.google.com/chrome/).
2. Open a terminal and navigate to the directory where the `.deb` file is located.
3. Run the following command to install it:

```sh
   sudo dpkg -i google-chrome-stable_current_amd64.deb

```

### Install Chrome GNOME Shell Integration

This command installs the Chrome GNOME Shell integration package. This allows for better integration between Google Chrome and the GNOME desktop environment, enabling features like media controls and notifications.

```sh
sudo apt install chrome-gnome-shell
```

### Install GNOME Shell Extension Manager

This command installs the GNOME Shell Extension Manager. This tool provides a convenient way to browse, install, update, and manage GNOME Shell extensions, which can add or modify the functionality and appearance of the GNOME desktop environment.

```sh
sudo apt install gnome-shell-extension-manager
```

### Install Git

This command installs Git, the widely-used distributed version control system. Git is essential for collaborating on software projects, tracking changes to files, and managing different versions of code.

```sh
sudo apt install git
```

### Install Visual Studio Code (VS Code) via Snap

This command installs Visual Studio Code using the Snap package manager. The `--classic` option is required because VS Code needs access to system resources beyond the typical Snap sandbox. Snaps provide a convenient way to install and manage applications, often including automatic updates.

```sh
sudo snap install code --classic
```
