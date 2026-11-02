# NetworkWalks Cybersecurity Lab Setup

## Overview
This repository documents my Week 1 cybersecurity lab setup for the NetworkWalks internship. The task involved installing and configuring Kali Linux in Oracle VirtualBox and verifying network connectivity.

## Lab Environment
- **Host Operating System:** Windows 10
- **Virtualization Software:** Oracle VirtualBox
- **Virtual Machine:** Kali Linux 2026.3
- **Network Mode:** NAT Network
- **Network Name:** NatNetwork
- **Network Subnet:** 10.0.0.0/24
- **Kali Linux IP Address:** 10.0.0.2/24
- **Default Gateway:** 10.0.0.1
- **DNS Servers:** 1.1.1.1 and 8.8.8.8

## Tasks Completed
1. Installed and configured Oracle VirtualBox.
2. Imported and started the Kali Linux virtual machine.
3. Configured the NAT Network and Kali Linux static IP address.
4. Verified internet connectivity and DNS resolution.
5. Enabled bidirectional Shared Clipboard and Drag and Drop.
6. Configured a shared folder between Windows and Kali Linux.
7. Created a VirtualBox snapshot named `Kali-Week1-Completed`.

## Network Connectivity Verification

The following commands were used to verify the network configuration:

```bash
ip -br a
```

```bash
ping -c 4 google.com
```

The ping test completed successfully with 0% packet loss.

## Shared Folder Configuration

A Windows folder named `downloads` was configured as a VirtualBox shared folder and mounted in Kali Linux at:

`/downloads`

## Troubleshooting

During the setup, I encountered network connectivity and IP address configuration issues. I resolved them by checking the network configuration, reconnecting the virtual machine's network connection, and ensuring the host computer had internet access.

After troubleshooting, Kali Linux successfully used the intended static IP configuration and internet connectivity was verified.

## Evidence and Screenshots

The following screenshots are included in this repository:

1. Kali Linux IP address and internet connectivity.
2. VirtualBox snapshot.
3. Shared folder configuration.
4. Bidirectional Shared Clipboard and Drag and Drop.

## Conclusion

The Week 1 cybersecurity lab environment was successfully configured. Kali Linux is running in VirtualBox with the intended network configuration, working internet connectivity, shared folder access, and a saved snapshot.
