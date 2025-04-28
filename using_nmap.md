# Using Nmap

Nmap (Network Mapper) is a powerful network scanning tool used to discover hosts and services on a computer network. It is an essential tool for network administrators and security professionals.

## Installation

1.  Download Nmap from the official website: [https://nmap.org/](https://nmap.org/)
2.  Install Nmap following the instructions for your operating system.

## Basic Scanning

*   **Scan a Single Host:** `nmap <target>` (e.g., `nmap 192.168.1.1`)
*   **Scan a Range of Hosts:** `nmap <target>` (e.g., `nmap 192.168.1.1-100`)
*   **Scan a Subnet:** `nmap <target>` (e.g., `nmap 192.168.1.0/24`)

## Common Scan Types

*   **TCP Connect Scan (-sT):** Establishes a full TCP connection to the target.
*   **SYN Scan (-sS):** Performs a stealthy scan by sending SYN packets and analyzing the responses.
*   **UDP Scan (-sU):** Scans for open UDP ports.
*   **Version Detection (-sV):** Determines the version of services running on open ports.
*   **OS Detection (-O):** Attempts to identify the operating system of the target.

## Example: Scanning a Host for Open Ports

1.  Open a terminal or command prompt.
2.  Type `nmap -sS <target>` (e.g., `nmap -sS 192.168.1.1`).
3.  Nmap will scan the target for open TCP ports using a SYN scan.
4.  The output will show the open ports and the services running on them.

## Example: Detecting the Operating System

1.  Open a terminal or command prompt.
2.  Type `nmap -O <target>` (e.g., `nmap -O 192.168.1.1`).
3.  Nmap will attempt to identify the operating system of the target.
4.  The output will show the detected operating system.

Nmap is a versatile tool that can be used for a wide range of network scanning tasks. By mastering Nmap, you can gain valuable insights into network infrastructure and improve your cybersecurity posture.
