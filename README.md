# Task-1# Local Network Port Scan Using Nmap

## Objective
This project demonstrates how to use Nmap to scan a local network (`192.168.1.0/24`) to identify active devices, detect open ports, and understand potential security risks.

## What is Port Scanning?
Port scanning is a technique used to discover open ports on devices within a network. Open ports indicate running services which may expose security vulnerabilities if not properly secured.

## Tools Used
- Nmap 7.97 (Linux)
- Bash terminal

## Command Used
```bash
nmap -sS 192.168.1.0/24
