# User-Log-Analysis-and-Monitoring-Script


# Log Analysis and Monitoring Script

## Purpose
This script automates the analysis and monitoring of log files.

## How to Use
1. Save the script as `log-monitor.sh`.
2. Make it executable using `chmod +x log-monitor.sh`.
3. Run the script with the desired keyword as an argument, for example: `./log-monitor.sh ERROR`.

## Features
- Monitors a specified log file for new entries in real-time.
- Searches for a specific keyword within log entries.
- Provides a summary report of keyword occurrences.
- Handles cleanup and exit using Ctrl+C.
- Checks for log file existence before monitoring.
- Allows for more advanced log analysis techniques and user interface improvements.

## Enhancements
1. **File Existence Checking**:
   - Before monitoring the log file, the script checks if the specified log file exists.
   - Displays an error message if the file doesn't exist.

2. **Advanced Log Analysis**:
   - Currently counts occurrences of a specific keyword in log entries.
   - Can be enhanced by implementing more sophisticated log analysis techniques.

3. **Improved User Interface**:
   - The user interface could be enhanced further by adding customization options and more interactive features.

Feel free to contribute and improve this script further!


