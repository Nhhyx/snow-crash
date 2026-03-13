Snow Crash is an introductory project into the world of cybersecurity.

## Project Overview

Snow Crash is designed to familiarize participants with essential concepts in cybersecurity, including:

![Snow Crash](https://github.com/Nhhyx/snow-crash/assets/62947287/391fdbf2-6f5c-4a48-b3f2-5d55067e809f)

[SPOILER ALERT]

- Deciphering Cesar code
- Conducting /etc/passwd attacks using John The Ripper
- Analyzing TCP flows on pcap files with Wireshark or tcpdump
- Modifying the PATH environment variable to execute binaries
- Exploiting vulnerabilities using Perl scripts
- Exploiting cron to execute binaries within a folder
- Identifying and exploiting PHP REGEX vulnerabilities
- Executing injection attacks through environment variables
- Bypassing code checks via symbolic links
- Reverse engineering hashed data

## Getting Started

### VM Setup - VirtualBox Network Configuration

We recommend setting up a VirtualBox Host-Only network.

- Select "Host-Only Network" in VirtualBox network settings.
- This configuration provides a private network between the host and the VM.

If there is no Host-Only Network configured:

- Go to "Tools" in VirtualBox and click on "Network".
- Select "Host-Only Network" and create a new one if none exists.
- Open the Networking section for your virtual machine and select "Host-only Network".
- Choose the host-only network from the drop-down list, preferably the one you just created.

### SSH Access

To access the VM via SSH

```bash
ssh -p 4242 levelXX@<ip>
```
