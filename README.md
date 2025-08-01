NAME-CHIRANJIB NAYAK
COMPANY-CODETECH IT SOLUTIONS
ID:CT04DZ554
DOMAIN-CYBER SECURITY AND ETHICAL HACKING
DURATION-18TH  JULY-18TH AUGUST 2025
MENTOR-NEELA SANTHOSH

PROJECT OVERVIEW:
Collecting workspace information

This project is a file change monitor implemented in Python. Its main purpose is to track changes (modifications, additions, deletions) in files within a specified directory over time.

Key features:

Calculates SHA-256 hashes for all files in a directory using [calculate_file_hash](c:\Users\chira\OneDrive\Desktop\internship task\file_monitor.py).
Scans the directory and builds a dictionary of file paths and their hashes with [scan_directory](c:\Users\chira\OneDrive\Desktop\internship task\file_monitor.py).
Stores and loads previous file hashes in a JSON file ([file_hashes.json](c:\Users\chira\OneDrive\Desktop\internship task\file_hashes.json)) using [save_hashes](c:\Users\chira\OneDrive\Desktop\internship task\file_monitor.py) and [load_previous_hashes](c:\Users\chira\OneDrive\Desktop\internship task\file_monitor.py).
Compares current and previous hashes to detect changes via [compare_hashes](c:\Users\chira\OneDrive\Desktop\internship task\file_monitor.py).
Provides a command-line interface to monitor a directory and optionally clear tracked hashes with [clear_hashes](c:\Users\chira\OneDrive\Desktop\internship task\file_monitor.py).
How it works:

User specifies a directory to monitor.
The script scans the directory, computes hashes, and compares them to the previous state.
It reports any changes (added, modified, deleted files) and updates the hash record for future scans.
The process repeats at a set interval (default: every 10 seconds).
All main logic is in [file_monitor.py](c:\Users\chira\OneDrive\Desktop\internship task\file_monitor.py).
