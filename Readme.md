# Network Printer Installation Tool [Version 1.01]

**Network Printer Installation Tool** is a command-line application designed to assist IT technicians in setting up network printers, specifically for **Canon** and **Ricoh** models. The tool automates the process of adding a network printer using their respective printer setup scripts, including printer drivers and port configuration.

---

## Features

- **RICOH Printer Setup**: Automates the installation of RICOH printers by configuring printer ports and installing the correct drivers.
- **Canon Printer Setup**: Automates the installation of Canon printers by configuring printer ports and installing the correct drivers.
- **User-Friendly Menu**: Offers a simple interface to select the printer model and proceed with the setup.
- **Exit Option**: Allows you to quit the program.

---

## Prerequisites

- **Windows Operating System** (The script uses Windows-specific tools like `cscript` and `rundll32`).
- **Administrator Privileges**: Some commands may require elevated permissions (run as administrator).
- **Printer Drivers**: Ensure the printer drivers for **Canon** and **Ricoh** are stored in the following directories:
  - Canon: `C:\Setup\Printer\NetPrinter\Driver\Canon\`
  - Ricoh: `C:\Setup\Printer\NetPrinter\Driver\Ricoh\`
  
  Replace these paths as needed if the drivers are located in different directories.

---

## Installation

Ensure you have Python 3.x installed.

### Required Python Modules
- `os`
- `time`
- `subprocess`

---

## Usage

### Running the Script

1. Clone this repository or download the script.
2. Open a terminal or command prompt.
3. Run the script using Python:

```bash
python printer_setup.py
