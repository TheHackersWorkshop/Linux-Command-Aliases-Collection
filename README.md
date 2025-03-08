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

bash
Copy
Edit
# Global Alias
if [ -f /etc/.aliases ]; then
    . /etc/.aliases
fi
Create a new alias file in /etc/.aliases and add the aliases you want to use from the provided list:

bash
Copy
Edit
sudo nano /etc/.aliases
Save the file and apply the changes by running:

bash
Copy
Edit
source ~/.bashrc  # or source ~/.zshrc
Now you can use your custom aliases globally across your system!
