# Relevant Anti-Virus Event
### Description

This detection method points out highly relevant Antivirus events

-------------------
### Severity

- High

-------------------
### Detailed Information
Looks for the following keywords:
  - HTool
  - Hacktool
  - ASP/Backdoor
  - JSP/Backdoor
  - PHP/Backdoor
  - Backdoor.ASP
  - Backdoor.JSP
  - Backdoor.PHP
  - Webshell
  - Portscan
  - Mimikatz
  - WinCred
  - PlugX
  - Korplug
  - Pwdump
  - Chopper
  - WmiExec
  - Xscan
  - Clearlog
  - ASPXSpy

-------------------
### Possible causes of false positives

- Some software piracy tools (key generators, cracks) are classified as hack tools

-------------------
### References

None

-------------------
### Supported Log Sources

- windows application

-------------------
