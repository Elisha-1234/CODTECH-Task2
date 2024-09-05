Name : Elisha E Cephas
Company : CODTECH IT SOLUTIONS 
ID : CT08DS7157
Domain : Cyber Security & Ethical Hacking 
Duration : August to September 2024
Mentor : Neela Santhosh Kumar 

Overview of this project 



Task: Create a simple vulnerability scanning tool that scans a network or website for common security vulnerabilities.

Objective: Identify potential security risks in a target network or website by detecting open ports, outdated software versions, and misconfigurations.

Functionality:

1. Port Scanning:
    - Use Nmap to scan the target network or website for open ports.
    - Identify potential entry points for attackers.
2. Outdated Software:
    - Send HTTP requests to the target website to gather HTML content.
    - Parse the HTML content using BeautifulSoup to extract version numbers.
    - Compare the extracted versions with a database or API to identify outdated software.
3. Misconfigurations:
    - Check for directory listing by searching for HTML links to directories.
    - Identify weak SSL/TLS cipher suites by analyzing the server response headers.

Requirements:

- Python programming language
- Nmap library for port scanning
- requests library for HTTP requests
- BeautifulSoup library for HTML parsing

Expected Output:

- A list of open ports
- A list of outdated software versions
- A boolean indicating whether directory listing is enabled
- A boolean indicating whether weak SSL/TLS cipher suites are used

Example Usage:

- Run the tool against a target network or website
- Review the output to identify potential security vulnerabilities
- Take necessary steps to address the identified vulnerabilities

Note: This is a basic example and should not be used in production without further development and testing. Additionally, ensure you have permission to scan the target network or website.
