
# Castor Data Extraction Tool

This tool automates data extraction from **Castor EDC** using **Selenium WebDriver** and processes the extracted data into structured formats for further analysis. 

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Disclaimer](#disclaimer)
- [License](#license)

---

## Features
- Connects to an already running Chrome browser session using the debugging port.
- Automatically navigates through Castor EDC participant data pages.
- Extracts text, form inputs, radio buttons, and checkboxes.
- Organizes extracted data in a structured format (`pandas` DataFrame).
- Handles pagination and overlays for seamless data extraction.

---

## Requirements
- Python 3.12+
- Chromium with debugging mode enabled
- ChromeDriver
- Python packages:
  - `selenium`
  - `pandas`

### Debugging Mode for Chrome
Run Chromium in debugging mode with the following command (Linux):
```sh
chromium --remote-debugging-port=9222 --user-data-dir=/tmp/chrome-user-data
```

---

## Disclaimer
This tool is designed for **personal use** only and should not be used for any unauthorized data access. Ensure compliance with your organization’s data protection policies and the terms of service of Castor EDC.

---

## License
[MIT License](LICENSE)

---
