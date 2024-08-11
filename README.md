
# Waybar Config

Welcome to the Waybar configuration repository! This folder contains custom configurations for Waybar, a highly customizable status bar for Wayland compositors. The configurations are designed to enhance the appearance and functionality of your Waybar setup.

## Folder Structure

- **`config`**: Contains the Waybar configuration file in TOML format.
- **`style.css`**: CSS file for customizing the appearance of Waybar.
- **`scripts/`**: Contains shell and Python scripts used for Waybar modules.

## Installation

1. **Install Waybar**: Follow the installation instructions for your Wayland compositor's preferred package manager or build from source.
   
2. **Place the Configuration Files**: Copy the contents of this repository to your Waybar configuration directory. This is usually located at `~/.config/waybar/`.

   ```bash
   cp -r path/to/this/repo/* ~/.config/waybar/

   Ensure Executable Permissions: Make sure all shell scripts in the scripts/ folder have executable permissions.

```
    chmod +x ~/.config/waybar/scripts/*.sh
```
# Configuration Files
1. config: The Waybar configuration file where you define modules, their positions, and their settings.
This file uses TOML syntax.

2. style.css: The CSS file for styling the Waybar.
Customize this file to change the appearance of your status bar. You can modify colors, fonts, spacing, and more.

3. Scripts
The scripts/ directory contains various scripts that provide dynamic content for your Waybar modules:

- Shell Scripts (*.sh): Used to fetch and format information for Waybar modules.
Examples include scripts for displaying system information or managing services.

- Python Scripts (*.py): Python-based scripts that provide more complex or data-intensive
content for Waybar modules. These scripts might include network statistics, weather updates, or custom alerts.


# Customization
Feel free to modify the CSS and scripts to suit your preferences. You can adjust the appearance
by editing style.css and change the content or functionality by updating the scripts.
