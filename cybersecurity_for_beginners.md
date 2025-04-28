# Cybersecurity for Beginners

## Introduction

Welcome to the world of cybersecurity! This guide provides an overview of essential concepts, threats, and tools to get you started.

## Core Concepts

### Confidentiality
Ensuring that information is accessible only to authorized individuals.

### Integrity
Maintaining the accuracy and completeness of information.

### Availability
Ensuring that authorized users have reliable access to information and resources when needed.

## Common Threats

### Malware
Malicious software designed to harm or disrupt systems.

*   **Types:** Viruses, worms, Trojans, ransomware, spyware, adware
*   **Example:** WannaCry ransomware

### Phishing
Deceptive attempts to acquire sensitive information (usernames, passwords, credit card details) by disguising as a trustworthy entity.

*   **Example:** Email pretending to be from your bank asking for account verification.

### Social Engineering
Manipulating individuals into divulging confidential information.

*   **Example:** Impersonating IT support to gain access to a user's credentials.

### Denial of Service (DoS) & Distributed Denial of Service (DDoS)
Overwhelming a system with traffic to make it unavailable to legitimate users.

*   **Example:** Sending a flood of requests to a web server.

### Man-in-the-Middle (MitM) Attack
Interception of communication between two parties without their knowledge.

*   **Example:** Intercepting data between a user and a Wi-Fi router.

### SQL Injection
Exploiting vulnerabilities in a database to inject malicious SQL code.

*   **Example:** Using a login form to inject SQL queries that bypass authentication.

## Basic Security Tools

### Antivirus Software
Detects and removes malware.

*   **Examples:** Windows Defender, McAfee, Norton

### Firewall
Monitors and controls network traffic based on predefined security rules.

*   **Examples:** Windows Firewall, iptables (Linux)

### Intrusion Detection System (IDS) / Intrusion Prevention System (IPS)
Detects and/or prevents malicious activity on a network or system.

*   **Examples:** Snort, Suricata

### Vulnerability Scanners
Identify security weaknesses in systems and applications.

*   **Examples:** Nessus, OpenVAS

### Password Managers
Securely store and manage passwords.

*   **Examples:** LastPass, 1Password

## Basic Security Practices

### Strong Passwords
Use a combination of uppercase and lowercase letters, numbers, and symbols.

*   **Example:** `P@$$wOrd123!`

### Multi-Factor Authentication (MFA)
Require multiple verification methods to access an account.

*   **Example:** Using a password and a code from your phone.

### Regular Software Updates
Keep your operating system and applications up to date to patch security vulnerabilities.

### Backups
Regularly back up your data to protect against data loss.

### Awareness
Stay informed about the latest security threats and best practices.

## Example Commands

### Linux

*   `ls -l`: List files with detailed information (permissions, size, etc.).
    ```bash
    ls -l
    ```
*   `sudo apt update`: Update the package list.
    ```bash
    sudo apt update
    ```
*   `sudo apt upgrade`: Upgrade installed packages.
    ```bash
    sudo apt upgrade
    ```
*   `netstat -tulnp`: Display listening network ports and associated processes.
    ```bash
    netstat -tulnp
    ```
*   `grep`: Search for specific patterns in files.
    ```bash
    grep "error" /var/log/syslog
    ```
*   `chmod`: Change file permissions.
    ```bash
    chmod 755 script.sh
    ```
*   `chown`: Change file owner.
    ```bash
    sudo chown user:group file.txt
    ```
*   `iptables`: Configure Linux firewall rules.
    ```bash
    sudo iptables -L
    ```

### Windows (PowerShell)

*   `Get-ChildItem`: List files and directories.
    ```powershell
    Get-ChildItem
    ```
*   `Get-Process`: List running processes.
    ```powershell
    Get-Process
    ```
*   `Test-Path`: Check if a file or directory exists.
    ```powershell
    Test-Path C:\example\file.txt
    ```
*   `Get-Service`: List services.
    ```powershell
    Get-Service
    ```
*   `Stop-Service`: Stop a service.
    ```powershell
    Stop-Service "ServiceName"
    ```
*   `Get-NetTCPConnection`: Display active TCP connections.
    ```powershell
    Get-NetTCPConnection
    ```

## Networking Basics

### IP Address
A unique address that identifies a device on a network.

*   **Example:** `192.168.1.1`

### Subnet Mask
Defines the network and host portions of an IP address.

*   **Example:** `255.255.255.0`

### Default Gateway
The IP address of the router that allows a device to access the internet.

*   **Example:** `192.168.1.254`

### DNS (Domain Name System)
Translates domain names to IP addresses.

*   **Example:** `8.8.8.8` (Google's Public DNS)

## Cryptography Basics

### Encryption
Converting data into a format that is unreadable without the correct key.

*   **Example:** AES, RSA

### Hashing
Creating a unique, fixed-size representation of data.

*   **Example:** SHA-256, MD5

### Digital Signatures
Using cryptography to verify the authenticity and integrity of a message.

## Conclusion

This guide provides a starting point for your cybersecurity journey. Continuous learning and hands-on practice are essential to becoming proficient in this field. Good luck!
