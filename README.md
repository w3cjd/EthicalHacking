# Ethical Hacking Project
### Password Cracking, Infrastructure Attacks, Enumeration &amp; Scanning, Reverse Hashing &amp; Decoding

Scope: Provided an encrypted archive, crack the password and host and investigate a website based on the decompressed files. Clues within this website reveal information about another system within the project environment, which is to be scanned for vulnerabilities and then exploited (including privilege escalation) using various methods.

- Used rar2john and John the Ripper tools to crack the password for a RAR archive.
- Hosted the decompressed PHP and CSS files using an Apache web server.
- Analyzed the website's source code, cookie storage, and network interactions for additional information.
- Decoded Base64 and performed reverse hashes using various algorithms to view obfuscated information.
- Scanned a Linux system for open ports and performed service and OS enumeration using nmap. Used various nmap features to evade IDS detection.
- Exported nmap system scan to a presentable HTML report.
- Used Metasploit to research exploits and attack a Linux system using multiple simultaneous attack vectors.
- Performed a privilege escalation attack once connceted into the Linux system to gain root permissions and capture the root user's password hash.

Full project scenario, overview, steps, and full documentation in the PDF report.

This course was part of my studies in the Cybersecurity Professional Bootcamp at the New Jersey Institute of Technology.
