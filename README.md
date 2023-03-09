# Cyber-Sec-Roadmap

* This Roadmap will help you in your journey to becoming RED-Teamer in Cyber-Sec field.

***

## Prerequisites

### Programming :
* Programming is use when you dig deep inside the Exploit Writing & making your own tools.
- `Basics of Python`
  - Python Interpreter
  - Working with PIP
  - Request Module
  - os module

- `Basics of C,CPP`
  - Input/output
  - Strings, pointers
  - This will Help you while reversing the executable...
- `Basics of Assembly`
  - Registers
  - Pointers
  - Architecture Based assemble...

### Networks :  
- Deep Understanding of `IP`- `Ipv4`,`Ipv6`
- `MAC`, MAC-Addressing, Mac-Spoofing
- `Data Packets` , How Data is fragmented into chunks
- `Headers & Payloads of data`
- `TCP/IP Stream`
- `Interfaces - LAN,WLAN,etc..`
- `Protocol - TCP, UDP`
- `Three-Way Handshake Working`
  - How Scanner use this 3-way handshake to fetch the version of application.
- `Network Devices`
- `HTTP`
  - HTTP Methods / Verbs
  - HTTP Headers
  - HTTP Response Code




### Linux Hardening
- `Basics Commands`
- `System Commands`
- `Piping & Redirecting`
- `Servers`
- `SSH`,  `TELNET`
- `Bash Scripting` 

### Windows Hardening
- `NTLM`
- `Lateral Movement`
- `Reverse shell`
- `powershell`
  - Uploading & Downloading
- `cmd`
  - Uploading & Downloading
  - Networks Commands
  - System Commands


***

## Hacking Flow :

### 01-Reconnaissance
- `Passive Recon`
  - whois 
  - Online tools...
- `Active Recon`
  - Host Discovery
    - Domains 
      - namp,nc,telnet
    - Subdomains
      - ffuf
      - wfuzz...
  - Network Scanning 
    - Port
    - IP-ranges
  - Directory Scanning
    - ffuf
    - gobuster
    - feroxbuster...
  - DNS-Recon
    - Dig,nslookup
  - Web-Recon
    - Browser-Developer tools
    - Robots, security.txt, js-files, cookies, Source-Page
    - API Testing, Admin-lookup..
    - Web-Vulnerability-Testing
### 02-Enumeration
- `FTP`
  - Anonymous Login
  - File Permission
  - Uploading shell 
- `SMB`
  - File Permission
  - File downloading
  - Uploading shell
 `NFS`
  - File Permission
  - mounting  & Unmounting
  - Uploading Shell
- `SMTP`
- `SSH`
- `TELNET`
- `DNS`
  - Dig
  - nslookup
  - dnsrecon

- `RCPBlind` + `NFS`

- `Web`
  - SQLi
  - Authentication Attack
  - Admin Panel 
    - Default Cred
    - Brute-force
    - Login with names that we get during the information gathering. 
    - Users Privilege Escalation
    - 
  - LFI,RFI
  - SSRF
  - RCE
  - File Upload Vulnerability
  - Access Control
  - SSTI
  - Serialization-Attack
  - JWT-Attacks
  - XXE
  - XXS, CSRF, CORS
  - Dom-based Vulnerability
  - Web-Sockets
  - HTTP Host Header Attacks
  - HTTP Request Smuggling
  - Prototype Pollution


### 03-Exploitation
- `Initial Access`
  - Initial access via web vulnerability.
    - RCE
    - Shell via admin panel Configuration. 
    - Wordpress php-404 web-shell upload.
    - Shell via Jenkins panel. 
    - SSH Brute-force by `www-data` or root, users...
 
- `Exploits`
  - Exploit Customizing
  - Exploit Writing

- `Payload Delivery`
  - Reverse-shell
  - Shell-Upload
  - `Upload page` Uploading in web directory  

- `Metasploit Framework`
- `Expoit-db`
- `Searchsploit`

### 04-Post-Exploitation
- `Lateral Movement`
- `Vertical & Horizontal Movement`
- `Containers`
  - Dockers instances.
- `Logs`
- `History`
- `Crontab`
- 
- `SUID,GUID Exploitation `
- `Writable permission for sudoers,passwd,shadow`
- `Pwntool`
- `Kernal Exploit`
- `Sudo Version`

### 05-Covering-Tracks
- `Mitigation`
- `Backdoors`


***

## Web-Exploitation
...
## Binary-Exploitation
...




















