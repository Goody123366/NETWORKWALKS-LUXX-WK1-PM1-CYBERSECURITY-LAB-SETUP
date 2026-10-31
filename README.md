 NETWORKWALKS-LUXX-WK1-PM1-CYBERSECURITY-LAB-SETUP
Week 1 Cybersecurity Lab Setup using VirtualBox and Kali Linux
Networkwalks Week 1 — Cybersecurity Lab Setup

Project Overview

This project involved setting up a cybersecurity practice lab using Oracle VirtualBox and Kali Linux as part of the Networkwalks Cybersecurity Internship.

Lab Requirements

- Oracle VirtualBox
- Kali Linux Virtual Machine
- 7-Zip

Steps Completed

1. VirtualBox NAT Network Configuration

Created a NAT Network in VirtualBox using the required IPv4 network range of "10.0.0.0/24".

"NAT Network Configuration" (01-NAT-Network-Configuration.png)

2. Kali Linux Virtual Machine Settings

Configured Shared Clipboard and Drag-and-Drop to Bidirectional in the Kali Linux virtual machine settings.

"Clipboard and Drag-and-Drop Settings" (02-Clipboard-Drag-Drop.png)

3. Kali Linux IP Configuration

Configured Kali Linux with the required IP address "10.0.0.2/24".

"Kali IP Configuration" (03-Kali-IP-Configuration.png)

4. Internet Connectivity Test

Tested internet connectivity using the ping command. Four packets were received with zero packet loss.

"Internet Connectivity Test" (04-Internet-Ping.png)

5. Shared Folder Configuration

Configured the host Downloads folder to be accessible inside Kali Linux at "/downloads". Verified the mount using "findmnt".

"Shared Folder Configuration" (05-Shared-Folder.png)

6. Virtual Machine Snapshot

Created a snapshot of the Kali Linux virtual machine after completing the lab setup.

"Kali VM Snapshot" (06-Kali-VM-Snapshot.png)

Troubleshooting Experience

During the network setup, I encountered an issue with network connectivity. I used NetworkManager commands to restart the wired connection and checked the Kali Linux IP configuration. After troubleshooting, the connection worked successfully, and the internet ping test completed with zero packet loss.

What I Learned

- How to configure a NAT Network in VirtualBox.
- How to configure a static IP address in Kali Linux.
- How to verify internet connectivity using "ping".
- How to configure and verify VirtualBox shared folders.
- How to create a virtual machine snapshot.
- The importance of troubleshooting network connectivity issues.

Conclusion

The Week 1 cybersecurity practice lab was configured successfully, and the main network, shared-folder, internet-connectivity, and snapshot requirements were completed.
