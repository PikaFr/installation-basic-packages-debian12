# Installation Script for Debian Packages

## Overview

This script automates the installation of essential packages on a fresh Debian 12 system. It helps you quickly set up a new environment with commonly used tools.

## What is it doing

The script performs the following tasks:

- Updates package repositories.
- Installs a set of essential packages for system administration and basic utilities. (sudo, htop, screen, openssh-server, unzip, curl, net-tools)

Feel free to customize the script by adding or removing packages based on your specific needs.

## How to Use

### Prerequisites

Make sure you are running the script on a Debian 12 system, you must also have downloaded wget (`apt-get install wget`) and you must be logged in as root.

### Download and Execute

To download and execute the script, use the following commands:

```bash
wget https://raw.githubusercontent.com/PikaFr/installation-basic-packages-debian12/main/install.sh
chmod +x install.sh
./install.sh
```

## Customization:
Edit the script to customize installed packages based on your needs.

### Download Link
[Download install.sh](https://raw.githubusercontent.com/PikaFr/installation-basic-packages-debian12/main/install.sh)
