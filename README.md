# hello-machine

A simple Bash script that greets you with your machine's hostname. Install it system-wide and run it anywhere in your terminal!

![Demo](https://img.shields.io/badge/demo-%F0%9F%91%8B-blue) ![License](https://img.shields.io/badge/license-MIT-green) ![Version](https://img.shields.io/badge/version-1.0.0-orange)

## Features
- Displays "Hello from [your-machine-name]" in the terminal
- Lightweight (2 lines of code!)
- No dependencies
- System-wide installation

## Installation

### Option 1: Install via APT (Debian/Ubuntu)
Add the repository and install with `apt`:
bash
# Add the repository
echo "deb [trusted=yes] https://raw.githubusercontent.com/abdelhakim-souilah/hello-machine/main/ ./" | sudo tee /etc/apt/sources.list.d/hello-machine.list

# Update package lists
sudo apt update

# Install the package
sudo apt install hello-machine
