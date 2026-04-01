# Python Projects For CyberSecurity

This repository contains small, educational Python scripts for learning practical cybersecurity basics.
Each script focuses on one concept (recon, scanning, password handling, or simple cryptography).


## What Is In This Repository

1. `PasswordGenerator.py` - Generates a random password using letters, numbers, and symbols.
2. `PortScanner.py` - Runs an Nmap scan through `python-nmap`.
3. `Whois.py` - Performs a WHOIS lookup using a socket connection.
4. `CryptoCipher.py` - Demonstrates Caesar cipher encryption/decryption.
5. `Directory-Brute-Forcing.py` - Tries directory paths from a wordlist against a target host.
6. `PasswordManager.py` - Simple in-memory account creation/login demo with SHA-256 hashing.
7. `dns_enum.py` - Enumerates common DNS record types (`A`, `MX`, `TXT`, etc.).
8. `subdomain_enum.py` - Attempts subdomain discovery with a subdomain wordlist.

## Requirements

- Python 3.10+ recommended
- Pip
- Optional system dependency for port scanning:
  - Nmap installed and accessible in PATH

## Install Python Packages

Install dependencies used by scripts in this project:

```bash
pip install requests dnspython python-nmap
```

## Run The Scripts

From the project root:

```bash
python PasswordGenerator.py
python PortScanner.py
python Whois.py
python CryptoCipher.py
python PasswordManager.py
python dns_enum.py example.com
python Directory-Brute-Forcing.py example.com wordlist.txt
python subdomain_enum.py example.com
```

## Notes By Script

- `PortScanner.py` requires Nmap installed locally.
- `Directory-Brute-Forcing.py` requires a custom `wordlist.txt`.
- `subdomain_enum.py` currently uses a hardcoded subdomain wordlist path in the source code. Update that path to a valid file on your machine before running.
- `PasswordManager.py` stores data in memory only (no database/file persistence).

## Suggested Next Improvements

- Add `requirements.txt`
- Add command-line arguments to all scripts for consistency
- Add input validation and better error handling
- Add tests and usage examples per script
# Simple Python Project For CyberSecurity



#### This scripts you can run in Windwos & Linux
## Projects Included

### 1. Password Generator
A secure password generator script that creates strong, random passwords using a customizable set of characters including letters, digits, and punctuation.

### 2. Port Scanner
A simple port scanner that checks the availability of specific ports on a given host, useful for identifying open ports and potential vulnerabilities.

### 3. WHOIS Lookup
A script to perform WHOIS lookups, providing information about the ownership and registration details of domain names.

### 4. Crypto Cipher
A script for basic encryption and decryption using ciphers. It demonstrates simple cryptographic techniques and how to implement them in Python.

### 5. Directory Brute Forcing
Directory brute-forcing involves systematically checking a list of potential directories and file names against a web server to discover hidden or non-publicly linked content.

### 6. Password Manager
A simple script that simulates the process of logging in and creating an account using only the username and password.

### 7. DNS Enumeration
A script for performing DNS enumeration to discover subdomains and other DNS records associated with a domain.

### 8. Subdomain Enumeration
A script for discovering subdomains associated with a target domain, useful for reconnaissance in penetration testing.

## Getting Started

To get started with any of these projects, clone the repository and navigate to the directory of the script you wish to run. Make sure you have Python installed on your system.

```bash
git clone https://github.com/vins254/Python-Project-For-CyberSecurity.git
cd Python-Project-For-CyberSecurity
