# Port Scanner

A simple TCP Port Scanner written in Python. This project scans a target host to identify open TCP ports using Python's built-in `socket` library.

## Features

* Scan a target by hostname or IP address
* Resolve hostnames to IP addresses
* Detect open TCP ports
* Display a clean banner using `pyfiglet`
* Handle common network errors gracefully

## Requirements

* Python 3
* pyfiglet

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/port-scanner.git
cd port-scanner
```

Install the required dependency:

```bash
pip install pyfiglet
```

## Usage

Run the script:

```bash
python3 port_scanner.py
```

Example:

```text
$ python3 port_scanner.py

PORT SCANNER

Enter a IP to scan: scanme.nmap.org

__________________________________________________
Scanning the following Host: 45.33.32.156
__________________________________________________

Port 22: is open
Port 80: is open
```

## How It Works

1. Displays a banner.
2. Prompts the user for a hostname or IP address.
3. Resolves the hostname to an IP address.
4. Scans TCP ports sequentially.
5. Prints all open ports found.

## Technologies Used

* Python 3
* socket
* pyfiglet
* subprocess
* sys
* time

## Learning Objectives

This project was created to practice:

* Python programming
* TCP networking fundamentals
* Socket programming
* Exception handling
* Building command-line tools

## License

This project is intended for educational purposes only.

Tu peux ensuite remplacer `your-username` par ton nom d'utilisateur GitHub avant de publier le dépôt.
