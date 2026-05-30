# Cybersecurity-Task-1-Port-Scanning

# Task 1 - Local Network Port Scan

## Objective
To identify open ports on devices connected to the local network using Nmap.

## Tools Used
- Nmap 7.99
- Windows Command Prompt

## Commands Used

1. Check Nmap installation

nmap --version


2. Find local IP address

ipconfig


3. Perform TCP SYN scan

nmap -sS 192.168.43.0/24


4. Save results

nmap -sS 192.168.43.0/24 -oN scan_results.txt


## Results

Active hosts found: 2

Open ports detected:

- 53/tcp (DNS)
- 135/tcp (MSRPC)
- 139/tcp (NetBIOS)
- 445/tcp (Microsoft-DS)
- 3306/tcp (MySQL)
- 3580/tcp

## Learning Outcome

- Learned Nmap installation and usage.
- Learned TCP SYN scanning.
- Learned how to identify active hosts.
- Learned how to identify open ports and services.

## Author

Sheelakshmi Dayanand
Elevate Labs Cyber Security Internship
