# Automating IP Access Control in Python

## Scenario
A healthcare organization manages a secure network environment dependent on strict IP allow lists. When access privileges are revoked, unauthorized IP addresses must be rapidly purged from system configurations to maintain compliance and security integrity[cite: 1].

## Project Overview
This project features a Python automation script that reads an enterprise allow list, compares it against a restricted removal list, filters out unauthorized IP addresses, and securely updates the source file[cite: 1].

## Tech Stack & Tools
* **Language:** Python[cite: 1]
* **Core Concepts:** File I/O, Error Mitigation, List Processing, Automated Access Auditing, Context Managers

## Key Features & Implementation
* **Safe File Management:** Utilizes Python's `with` statement context manager to safely open, read, and write to files without resource leaks[cite: 1].
* **Data Transformation:** Converts raw string data into dynamic Python lists using `.split()` for granular element manipulation[cite: 1].
* **Algorithmic Filtering:** Implements conditional `for` loops combined with membership operators (`in`) to evaluate and prune targeted IPs[cite: 1].
* **File Persistence:** Serializes the cleaned list back into a string via `.join()` before overwriting the target file in write (`"w"`) mode[cite: 1].

## Key Learning Outcomes & Reflections
* **Practical Automation:** Demonstrated how to translate manual administrative workflows into efficient, repeatable code.
* **Data Type Handling:** Reinforced the critical importance of properly managing data transformations between string buffers and list collections during file I/O operations.

## Lab Documentation
You can view the original project guidelines and step-by-step instructions here:
📄 [View Project PDF Guide](docs/Algorithm%20for%20file%20updates%20in%20Python.pdf)

## Author
Aspiring Cybersecurity Analyst | SOC Analyst | Incident Response | Threat Detection | Network Security | Log Analysis
