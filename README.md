# Installing Multiple Python Versions

This guide will help you install a specific Python version (e.g., Python 3.11) on a Linux system, such as Ubuntu, using the `deadsnakes` repository. By following these steps, you'll be able to manage and utilize multiple Python versions on your system.

## Prerequisites

Before you start, ensure your package list is up to date and that any unnecessary packages are removed.

```
sudo apt update
sudo apt upgrade
sudo apt install software-properties-common
sudo apt autoremove
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update
sudo apt install python3.11
sudo apt install python3.11-distutils
wget https://bootstrap.pypa.io/get-pip.py
sudo python3.11 get-pip.py
pip --version
python3.11 -m pip --version
```
