# Port Scanner

A simple TCP Port Scanner written in Python. This project scans a target host to identify open TCP ports using Python's built-in `socket` library.

---

## Preview

```text
██████╗  ██████╗ ██████╗ ████████╗    ███████╗ ██████╗ █████╗ ███╗   ██╗███╗   ██╗███████╗██████╗
██╔══██╗██╔═══██╗██╔══██╗╚══██╔══╝    ██╔════╝██╔════╝██╔══██╗████╗  ██║████╗  ██║██╔════╝██╔══██╗
██████╔╝██║   ██║██████╔╝   ██║       ███████╗██║     ███████║██╔██╗ ██║██╔██╗ ██║█████╗  ██████╔╝
██╔═══╝ ██║   ██║██╔══██╗   ██║       ╚════██║██║     ██╔══██║██║╚██╗██║██║╚██╗██║██╔══╝  ██╔══██╗
██║     ╚██████╔╝██║  ██║   ██║       ███████║╚██████╗██║  ██║██║ ╚████║██║ ╚████║███████╗██║  ██║
╚═╝      ╚═════╝ ╚═╝  ╚═╝   ╚═╝       ╚══════╝ ╚═════╝╚═╝  ╚═╝╚═╝  ╚═══╝╚═╝  ╚═══╝╚══════╝╚═╝  ╚═╝
```


=================================================================
 Author      : Farid Riani
 Version     : 1.0
 Description : Simple TCP Port Scanner written in Python
=================================================================

Enter an IP or Hostname to scan:
```

Or with a screenshot:

![Port Scanner Preview](images/banner.png)

---

## Features

- Scan a target by hostname or IP address
- Resolve hostnames to IP addresses
- Detect open TCP ports
- Display a banner using `pyfiglet`
- Handle common network errors gracefully

## Requirements

- Python 3
- pyfiglet

## Installation

```bash
git clone https://github.com/Rianifarid/port-scanner.git
cd port-scanner
pip install pyfiglet
```

## Usage

```bash
python3 port_scanner.py
```

Example:

```text
Enter an IP or Hostname to scan: scanme.nmap.org

=============================================================
Scanning Target : 45.33.32.156
=============================================================

Port 22: is open
Port 80: is open
Port 443: is open
```

## Technologies Used

- Python 3
- socket
- pyfiglet
- subprocess
- sys
- time

## Learning Objectives

This project was created to practice:

- Python programming
- Socket programming
- TCP networking
- Exception handling
- Building command-line security tools

## License

This project is intended for educational purposes only.
