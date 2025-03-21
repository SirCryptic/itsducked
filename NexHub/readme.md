![image](https://github.com/user-attachments/assets/63b7bcba-93e5-41a5-960d-a60b1afa9ec9)


# NexHub

A compact tool designed for penetration testers to set up listeners and a file server alongside **Ducky** scripts. NexHub simplifies managing Ncat listeners and hosting files for exfiltration or payload delivery during pentesting.

## Features
- **Listener Setup**: Configure and start Ncat listeners for Rubber Ducky payloads.
- **File Server**: Host files for easy access or exfiltration via a web interface.
- **Upload Management**: Upload files with overwrite prompts for control.
- **Pentesting Focus**: Built to streamline BadUSB Attack workflows.

## Usage
1. Launch `NexHub.ps1` with admin rights.
2. Start the listener (option 2) for Ducky script callbacks.
3. Start the server (option 3) to host files at `http://<serverIP>:80`.

## Requirements
- PHP (for the server)
- Ncat (from Nmap)
- Windows PowerShell

Developed by SirCryptic for pentesting efficiency.
