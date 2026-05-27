# OSCP

## Columns

### 01. Information Gathering

- [01.01 Active Port Service Discovery nmap](01.-information-gathering/01.01-active-port-service-discovery-nmap.md)
- [01.02 DNS SMTP SNMP Enumeration](01.-information-gathering/01.02-dns-smtp-snmp-enumeration.md)
- [01.03 Passive OSINT](01.-information-gathering/01.03-passive-osint.md)
- [01.04 SMB RPC NetBIOS Enumeration](01.-information-gathering/01.04-smb-rpc-netbios-enumeration.md)

### 02. Vulnerability Scanning

- [02.01 Lightweight Vuln Scan with Nmap NSE](02.-vulnerability-scanning/02.01-lightweight-vuln-scan-with-nmap-nse.md)
- [02.02 Nessus Basics](02.-vulnerability-scanning/02.02-nessus-basics.md)
- [02.03 Web Vuln Scanning nikto wpscan](02.-vulnerability-scanning/02.03-web-vuln-scanning-nikto-wpscan.md)

### 03. Introduction to Web Applications

- [03.01 Cross-Site Scripting XSS](03.-introduction-to-web-applications/03.01-cross-site-scripting-xss.md)
- [03.02 Web App Enum Methodology](03.-introduction-to-web-applications/03.02-web-app-enum-methodology.md)

### 04. Common Web Application Attacks

- [04.01 Directory Traversal](04.-common-web-application-attacks/04.01-directory-traversal.md)
- [04.02 File Upload Bypass → Webshell](04.-common-web-application-attacks/04.02-file-upload-bypass-webshell.md)
- [04.03 Local File Inclusion LFI → RCE](04.-common-web-application-attacks/04.03-local-file-inclusion-lfi-rce.md)
- [04.04 OS Command Injection](04.-common-web-application-attacks/04.04-os-command-injection.md)
- [04.05 Remote File Inclusion RFI](04.-common-web-application-attacks/04.05-remote-file-inclusion-rfi.md)

### 05. SQL Injection Attacks

- [05.01 Blind Boolean Time SQLi](05.-sql-injection-attacks/05.01-blind-boolean-time-sqli.md)
- [05.02 Manual SQLi Detection](05.-sql-injection-attacks/05.02-manual-sqli-detection.md)
- [05.03 MSSQL xp_cmdshell from SQLi](05.-sql-injection-attacks/05.03-mssql-xp_cmdshell-from-sqli.md)
- [05.04 sqlmap Automation](05.-sql-injection-attacks/05.04-sqlmap-automation.md)
- [05.05 UNION-based Extraction](05.-sql-injection-attacks/05.05-union-based-extraction.md)

### 06. Client-Side Attacks

- [06.01 LNK Library Files](06.-client-side-attacks/06.01-lnk-library-files.md)
- [06.02 Office Macros HTA Word](06.-client-side-attacks/06.02-office-macros-hta-word.md)

### 07. Locating Public Exploits

- [07.01 Exploit-DB SearchSploit](07.-locating-public-exploits/07.01-exploit-db-searchsploit.md)
- [07.02 GitHub PoC Hunting](07.-locating-public-exploits/07.02-github-poc-hunting.md)

### 08. Fixing Exploits

- [08.01 Adapt Memory Corruption Exploits](08.-fixing-exploits/08.01-adapt-memory-corruption-exploits.md)
- [08.02 Fix Web Exploits](08.-fixing-exploits/08.02-fix-web-exploits.md)

### 09. Antivirus Evasion

- [09.01 AMSI Bypass](09.-antivirus-evasion/09.01-amsi-bypass.md)
- [09.02 Encoding Custom Loaders](09.-antivirus-evasion/09.02-encoding-custom-loaders.md)

### 10. Password Attacks

- [10.01 Hash Cracking](10.-password-attacks/10.01-hash-cracking.md)
- [10.02 Pass-the-Hash Net-NTLMv2 Relay](10.-password-attacks/10.02-pass-the-hash-net-ntlmv2-relay.md)
- [10.03 Service Brute-Force hydra netexec](10.-password-attacks/10.03-service-brute-force-hydra-netexec.md)
- [10.04 Wordlist Mutation](10.-password-attacks/10.04-wordlist-mutation.md)

### 11. Windows Privilege Escalation

- [11.01 Enumeration winPEAS Seatbelt](11.-windows-privilege-escalation/11.01-enumeration-winpeas-seatbelt.md)
- [11.02 Scheduled Tasks AlwaysInstallElevated](11.-windows-privilege-escalation/11.02-scheduled-tasks-alwaysinstallelevated.md)
- [11.03 Sensitive File Registry Hunting](11.-windows-privilege-escalation/11.03-sensitive-file-registry-hunting.md)
- [11.04 Service Binary Hijacks](11.-windows-privilege-escalation/11.04-service-binary-hijacks.md)
- [11.05 Token Privilege Abuse SeImpersonate](11.-windows-privilege-escalation/11.05-token-privilege-abuse-seimpersonate.md)

### 12. Linux Privilege Escalation

- [12.01 Cron Job Hijack](12.-linux-privilege-escalation/12.01-cron-job-hijack.md)
- [12.02 Enumeration linPEAS](12.-linux-privilege-escalation/12.02-enumeration-linpeas.md)
- [12.03 Kernel PwnKit-class](12.-linux-privilege-escalation/12.03-kernel-pwnkit-class.md)
- [12.04 sudo Misuse](12.-linux-privilege-escalation/12.04-sudo-misuse.md)
- [12.05 SUID Capabilities GTFOBins](12.-linux-privilege-escalation/12.05-suid-capabilities-gtfobins.md)

### 13. Port Redirection and SSH Tunneling

- [13.01 Socat Plink Netsh](13.-port-redirection-and-ssh-tunneling/13.01-socat-plink-netsh.md)
- [13.02 SSH Local Remote Dynamic](13.-port-redirection-and-ssh-tunneling/13.02-ssh-local-remote-dynamic.md)

### 14. Tunneling Through Deep Packet Inspection

- [14.01 DNS Tunneling with dnscat2](14.-tunneling-through-deep-packet-inspection/14.01-dns-tunneling-with-dnscat2.md)
- [14.02 HTTP Tunneling with Chisel](14.-tunneling-through-deep-packet-inspection/14.02-http-tunneling-with-chisel.md)

### 15. The Metasploit Framework

- [15.01 Metasploit Workflow](15.-the-metasploit-framework/15.01-metasploit-workflow.md)
- [15.02 Meterpreter Post-Exploitation](15.-the-metasploit-framework/15.02-meterpreter-post-exploitation.md)
- [15.03 msfvenom Payload Generation](15.-the-metasploit-framework/15.03-msfvenom-payload-generation.md)

### 16. Active Directory Introduction and Enumeration

- [16.01 BloodHound SharpHound](16.-active-directory-introduction-and-enumeration/16.01-bloodhound-sharphound.md)
- [16.02 Legacy Tools net.exe setspn](16.-active-directory-introduction-and-enumeration/16.02-legacy-tools-net.exe-setspn.md)
- [16.03 PowerView Triage Queries](16.-active-directory-introduction-and-enumeration/16.03-powerview-triage-queries.md)

### 17. Attacking Active Directory Authentication

- [17.01 AS-REP Roasting](17.-attacking-active-directory-authentication/17.01-as-rep-roasting.md)
- [17.02 DCSync](17.-attacking-active-directory-authentication/17.02-dcsync.md)
- [17.03 Golden Ticket](17.-attacking-active-directory-authentication/17.03-golden-ticket.md)
- [17.04 Kerberoasting](17.-attacking-active-directory-authentication/17.04-kerberoasting.md)
- [17.05 Silver Ticket Forging](17.-attacking-active-directory-authentication/17.05-silver-ticket-forging.md)

### 18. Lateral Movement in Active Directory

- [18.01 DCOM Lateral MMC20](18.-lateral-movement-in-active-directory/18.01-dcom-lateral-mmc20.md)
- [18.02 Pass-the-Hash Overpass-the-Hash](18.-lateral-movement-in-active-directory/18.02-pass-the-hash-overpass-the-hash.md)
- [18.03 PsExec SMBExec WMIExec](18.-lateral-movement-in-active-directory/18.03-psexec-smbexec-wmiexec.md)
- [18.04 WinRM evil-winrm](18.-lateral-movement-in-active-directory/18.04-winrm-evil-winrm.md)

### 19. Assembling the Pieces

- [19.01 Domain Foothold → DA](19.-assembling-the-pieces/19.01-domain-foothold-da.md)
- [19.02 Internal Recon Post-Pivot](19.-assembling-the-pieces/19.02-internal-recon-post-pivot.md)
- [19.03 Public Network → Foothold](19.-assembling-the-pieces/19.03-public-network-foothold.md)

