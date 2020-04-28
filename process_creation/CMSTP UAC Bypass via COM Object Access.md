# CMSTP UAC Bypass via COM Object Access
### Description

Detects UAC Bypass Attempt Using Microsoft Connection Manager Profile Installer Autoelevate-capable COM Objects

-------------------
### Severity

- High

-------------------

### Detailed Information

Triggers On launch of DllHost.exe by parent process with UUID 3E5FC7F9-9A51-4367-9063-A120244FBEC7 or 3E000D72-A845-4CD9-BD83-80C07C3B881F

-------------------

### Possible causes of false positives

- Legitimate CMSTP use (unlikely in modern enterprise environments)


-------------------
### References

- http://www.endurant.io/cmstp/detecting-cmstp-enabled-code-execution-and-uac-bypass-with-sysmon/
- https://twitter.com/hFireF0X/status/897640081053364225

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
