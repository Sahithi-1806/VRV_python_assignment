# VRV_python_assignment

# Log Analysis Tool

This repository contains a Python script to analyze server log files and extract valuable insights, such as:
- The number of requests per IP address.
- The most accessed endpoint.
- Suspicious activities, such as failed login attempts exceeding a specified threshold.

## Features
1. **Requests per IP**: Counts the number of requests made by each IP address.
2. **Most Accessed Endpoint**: Identifies the endpoint with the highest number of accesses.
3. **Suspicious Activity Detection**: Detects failed login attempts (`401` errors or "Invalid credentials") and highlights IPs exceeding a predefined threshold.

## How It Works
1. The script reads the log file `sample.log` and processes its content line by line.
2. Regular expressions (`regex`) are used to extract IP addresses and endpoints from the log file.
3. The following analysis is performed:
   - Count of requests per IP.
   - Detection of the most accessed endpoint.
   - Identification of suspicious activity based on failed login attempts.

4. The results are saved to a CSV file (`log_analysis_results.csv`).

-> Usage

->Prerequisites
- Python 3.x installed on your machine.
- Ensure the log file (`sample.log`) is present in the same directory as the script.

