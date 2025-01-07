# Home-SIEM-Lab

# PROJECTNAME

## Objective
The Vulnerability Assessment and Penetration Testing (VAPT) project aimed to simulate real-world cyberattacks on a target system or network to identify potential vulnerabilities. The goal was to assess the security posture by performing active penetration testing and generating realistic attack scenarios. This hands-on experience provided an in-depth understanding of security risks, common vulnerabilities, and attack techniques, while reinforcing the importance of security measures to protect critical infrastructure.

### Skills Learned

- Mastery of penetration testing techniques and methodologies.
- Ability to identify and exploit vulnerabilities in various systems and applications.
- Knowledge of web application security and common vulnerabilities such as SQL injection, XSS, and RCE.
- Proficiency in using tools for vulnerability scanning, exploitation, and post-exploitation.
- Strengthened understanding of ethical hacking practices and legal implications.

### Tools Used

- **Kali Linux** for penetration testing and security auditing.
- **Burp Suite** for web vulnerability scanning and exploitation.
- **Metasploit Framework** for exploitation and post-exploitation.
- **Nmap** for network discovery and vulnerability scanning.
- **OWASP ZAP** for automated security testing of web applications.
- **Wireshark** for network traffic analysis.

## Steps

Below are the key steps taken in the VAPT process:

### 1. Reconnaissance and Information Gathering
In the reconnaissance phase, initial information about the target system was gathered through open-source intelligence (OSINT), social engineering, and network scanning techniques.

*Ref 1: Nmap Scan Results*  
This screenshot shows the results of a network scan using Nmap, identifying open ports and services on the target machine.

![Nmap Scan](link-to-image)

### 2. Vulnerability Scanning
During this phase, tools like Nessus and OpenVAS were used to identify vulnerabilities in the system and applications, categorizing them based on severity.

*Ref 2: Nessus Scan Report*  
Here, Nessus scan results display a list of detected vulnerabilities, ranked by their criticality.

![Nessus Scan](link-to-image)

### 3. Exploitation
Once vulnerabilities were identified, exploitation techniques were employed to verify their existence and assess their impact.

*Ref 3: Metasploit Exploit*  
This screenshot shows a successful exploit using Metasploit, gaining unauthorized access to the target system.

![Metasploit Exploit](link-to-image)

### 4. Post-Exploitation
Post-exploitation focused on maintaining access and escalating privileges to gather sensitive information or pivot to other systems within the network.

*Ref 4: Post-Exploitation Shell*  
This image captures the post-exploitation shell session, where elevated privileges were used to extract sensitive data.

![Post-Exploitation Shell](link-to-image)

### 5. Reporting
Finally, all findings were documented, including detailed descriptions of vulnerabilities, exploits, and remediation recommendations.

*Ref 5: Vulnerability Report*  
This screenshot shows a portion of the penetration testing report, highlighting critical vulnerabilities and suggested fixes.

![Vulnerability Report](link-to-image)
