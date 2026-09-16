# Automating IP Access Control in Python

## Scenario
A healthcare organization manages a secure network environment dependent on strict IP allow lists. When access privileges are revoked, unauthorized IP addresses must be rapidly purged from system configurations to maintain compliance and security integrity.

## Project Overview
This project features a Python automation script that reads an enterprise allow list, compares it against a restricted removal list, filters out unauthorized IP addresses, and securely updates the source file.

## Tech Stack & Tools
* **Language:** Python
* **Core Concepts:** File I/O, Error Mitigation, List Processing, Automated Access Auditing, Context Managers

## Key Features & Implementation
* **Safe File Management:** Utilizes Python's `with` statement context manager to safely open, read, and write to files without resource leaks.
* **Data Transformation:** Converts raw string data into dynamic Python lists using `.split()` for granular element manipulation.
* **Algorithmic Filtering:** Implements conditional `for` loops combined with membership operators (`in`) to evaluate and prune targeted IPs.
* **File Persistence:** Serializes the cleaned list back into a string via `.join()` before overwriting the target file in write (`"w"`) mode.

## Key Learning Outcomes & Reflections
* **Practical Automation:** Demonstrated how to translate manual administrative workflows into efficient, repeatable code.
* **Data Type Handling:** Reinforced the critical importance of properly managing data transformations between string buffers and list collections during file I/O operations.

## Documentation

 **[Algorithm for File Updates in Python (PDF)](./Algorithm_For_File_Updates_In_Python.pdf)**

## Author
Saba Fatima

Aspiring Cybersecurity Analyst | SOC Analyst | Incident Response | Threat Detection | Network Security | Log Analysis
