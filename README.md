# Linux-Command-Aliases-Collection
This script provides a comprehensive set of aliases to streamline system administration, package management, file operations, networking, and user commands in Linux environments. It enhances efficiency by simplifying common commands and integrating useful scripts.

Features:
System Management: Quick access to updates, package installations, service management, and shutdown commands.
File Operations: Simplified commands for copying, moving, deleting, and checking disk usage.
Monitoring Tools: Shortcuts for htop, neofetch, cpufetch, and custom scripts like check_permissions.py.
Service Controls: Easily start, stop, enable, disable, or check the status of system and user services.
Networking: Handy aliases for running ping, nmap, and network configuration scripts.
Custom Scripts: Includes user-defined Python and Bash scripts for various automation tasks.
Usage:
Add the following lines to the end of your ~/.bashrc or ~/.zshrc file:


# Global Alias
if [ -f /etc/.aliases ]; then
    . /etc/.aliases
fi
Create a new alias file in /etc/.aliases and add the aliases you want to use from the provided list:


sudo nano /etc/.aliases

Save the file and apply the changes by running:


source ~/.bashrc  # or source ~/.zshrc

Important Note:
Most aliases in this collection start with a capital letter to clearly indicate that they are aliases and to prevent conflicts with regular system commands. For example:

#Update instead of update
#Install instead of install
#Reboot instead of reboot

This ensures that the original system commands remain available while making the aliases easy to identify and use.

Now you can enjoy a more efficient command-line experience with custom aliases!

**I know there are a few aliases that do not follow the capital letter convension but this is the why I use it.
