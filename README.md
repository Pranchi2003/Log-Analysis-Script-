# Log-Analysis-Script-
This Python script analyzes a web server log file (sample.log) to extract and analyze key data, specifically focusing on identifying potential security issues and patterns of usage. The script performs the following tasks:

1. Requests per IP: Counts and displays the number of requests made by each IP address, sorted by frequency.
2. Most Accessed Endpoint: Identifies the most frequently accessed resource (e.g., /home) and its count.
3. Suspicious Activity Detection: Flags IPs with failed login attempts (e.g., status 401) exceeding a configurable threshold, helping identify potential brute force attacks.
4. Output: Results are displayed in the terminal and saved in a structured CSV file.
5. This script is useful for log analysis, usage patterns, and basic security monitoring.
