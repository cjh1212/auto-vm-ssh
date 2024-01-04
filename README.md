# QEMU Automation with SSH Access

## Introduction
This repository contains a Bash and Expect script designed to automate the deployment and management of QEMU instances. It simplifies the process of setting up a virtual machine and makes it accessible via SSH to remote devices.

## Features
- **Automated QEMU Instance Creation:** Streamline the setup of QEMU virtual machines with minimal user input.
- **Remote SSH Access:** Configure your VMs to be accessible remotely via SSH, enabling efficient management and operation.
- **Customizable Scripts:** Easily adaptable scripts to fit specific needs and environments.

## Prerequisites
Before you begin, ensure you have the following installed:
- Bash
- Expect
- QEMU
- SSH
- Personal VPN (optional)

## Configuration
- Edit `config.sh` to adjust QEMU settings like memory, CPU, and disk size as per your requirements.
- Update `ssh_config` to set up remote SSH access parameters.
    - Default: serveo.net
