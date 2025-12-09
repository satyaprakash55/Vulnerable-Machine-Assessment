# Vulnerable-Machine-Assessment
This repository covers a hands-on penetration test of a vulnerable .ova VM. Using Nmap, port enumeration, web testing, and OWASP-aligned analysis, all findings, screenshots, and PoCs are in the Report/ directory, demonstrating methodical real-world security assessment skills.

This repository contains documentation and results for the Vulnerable Machine REATIME assessment test. This virtual machine is intentionally vulnerable and was used for controlled testing and learning purposes.

Table of Contents

Overview

Setup Instructions

Accessing the Application

Assessment Notes

Disclaimer

Overview

The goal of this assessment was to explore and interact with a deliberately vulnerable machine. This helped practice penetration testing techniques and understand security vulnerabilities in a controlled environment.

Setup Instructions

Importing the Machine

Download and install Oracle VirtualBox
.

Import the provided xberses.ova file into VirtualBox.

After importing, the virtual machine will appear in your VirtualBox list.

Starting the Machine

Select the imported VM and click Start.

The machine will boot automatically to the login screen.

Use the following credentials to log in:

Username: xxxxx..

Password: xxxxx..

Network Setup

Configure the VM network adapter as Bridged Adapter (or Host-Only Adapter if needed).

Once booted, the VM will automatically receive an IP address.

Example: 192.168.X.X

Accessing the Application

Open a web browser on your host machine.

Enter the VM's IP address with the port 8080 in the format:

http://192.168.X.X:8080


The vulnerable web application will load.

The application is intentionally vulnerable. Use the credentials 123pas as needed for login or testing.

Assessment Notes

All findings and results from this assessment have been documented in this repository.

This VM is strictly for assessment purposes and should not be exposed to the internet.

If you encounter network issues, ensure the VM network adapter is properly configured.

Disclaimer

This virtual machine and its application are intentionally vulnerable for learning and assessment purposes only. Do not use this outside the controlled environment.
