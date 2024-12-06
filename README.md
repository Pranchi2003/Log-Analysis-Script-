# Log-Analysis-Script-
This Python script analyzes a web server log file (sample.log) to extract key insights:

Requests per IP: Counts and displays the number of requests made by each IP address, sorted by frequency.
Most Accessed Endpoint: Identifies the most frequently accessed resource (e.g., /home) and its count.
Suspicious Activity Detection: Flags IPs with failed login attempts (e.g., status 401) exceeding a configurable threshold, helping identify potential brute force attacks.
Output: Results are displayed in the terminal and saved in a structured CSV file.
This script is useful for log analysis, usage patterns, and basic security monitoring.
