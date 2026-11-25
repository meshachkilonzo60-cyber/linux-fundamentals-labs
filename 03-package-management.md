# Linux Fundamentals Lab 03: Package Management

## Objective
Understand how to update system repositories, install, remove and manage software packages in Linux.

## Environment
- Operating System: Kali Linux
- Package Manager: APT
- Shell: Bash

## Commands Practiced

| Command | Description |
|---|---|
| `sudo apt update` | Refreshes available package information |
| `sudo apt upgrade` | Upgrades installed packages |
| `sudo apt install package-name` | Installs a software package |
| `sudo apt remove package-name` | Removes an installed package |
| `sudo apt purge package-name` | Removes a package and its system configuration files |
| `sudo apt autoremove` | Removes automatically installed packages that are no longer required |
| `apt search package-name` | Searches for available packages |
| `apt show package-name` | Displays package information |
| `dpkg -l` | Lists installed packages |
| `sudo apt clean` | Clears downloaded package files from the local cache |

## Practical Exercises

### 1. Updating package information
```bash
sudo apt update
```

### 2. Upgrading installed software
```bash
sudo apt upgrade
```

### 3. Searching for a package
```bash
apt search package-name
```

### 4. Installing software
```bash
sudo apt install package-name
```

### 5. Removing software
```bash
sudo apt remove package-name
```

### 6. Viewing package information
```bash
apt show package-name
```

### 7. Listing installed packages
```bash
dpkg -l
```

### 8. Cleaning package cache
```bash
sudo apt clean
```

## Key Lessons
- APT is a package management tool used in Debian-based Linux distributions.
- `apt update` refreshes package information but does not upgrade installed software.
- `apt upgrade` installs available upgrades.
- `apt install` installs software packages.
- `apt remove` uninstalls software while generally retaining configuration files.
- `apt purge` removes software and its system configuration files.

## Cybersecurity Relevance
Package management helps cybersecurity professionals install security tools, maintain updated systems, manage software dependencies and remove unnecessary applications that may increase the attack surface.

## Status
Commands documented. Practical completion to be verified.
