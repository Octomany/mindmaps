# Hack The Box Machine - Note Taking Template

## Machine Information
- **Machine Name:** 
- **IP Address:** 
- **OS:** 
- **Difficulty:** 
- **Status:** 

## Enumeration
- **Network Scanning**
  - Nmap Scan:
    ```
    nmap -sC -sV -oN scan_results.txt <TARGET_IP>
    ```
  - Open Ports:
    - Port 22 (SSH)
    - Port 80 (HTTP)
    - Port 443 (HTTPS)
    - ...

## Web Application Enumeration
- **Directory Brute Forcing**
  - Tool Used: dirb
  - Command:
    ```
    dirb http://<TARGET_IP> /usr/share/wordlists/dirb/common.txt
    ```
  - Discovered Directories:
    - /admin
    - /backup
    - ...

## Exploitation
- **Web Application Exploitation**
  - **Vulnerability:** SQL Injection
    - Payload: `' OR 1=1--`
    - Result: Dumped database
  - **Vulnerability:** Command Injection
    - Payload: `;ls`
    - Result: Listed directory contents

## Privilege Escalation
- **Kernel Exploits**
  - Exploit Used: DirtyCow
  - Command:
    ```
    searchsploit dirtycow
    ```

## Post-Exploitation
- **Persistence**
  - Backdoor Installed: Yes
  - Location: /tmp/backdoor.sh
- **Data Exfiltration**
  - Files Extracted: /etc/passwd, /etc/shadow
- **Covering Tracks**
  - Logs Cleared: Yes
  - Command:
    ```
    rm -rf /var/log/*
    ```

## Additional Notes
- Insert any additional notes or observations here.

## Tools Used
- List of tools used during the engagement:
  - Nmap
  - dirb
  - sqlmap
  - Metasploit
  - ...

## References
- Links to any relevant write-ups, articles, or documentation.
