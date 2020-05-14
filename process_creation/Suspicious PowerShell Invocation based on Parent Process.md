# Suspicious PowerShell Invocation based on Parent Process
### Description

Detects suspicious powershell invocations from interpreters or unusual programs.

-------------------
### Severity

Medium

-------------------

### Detailed Information

Triggers when Powershell is invoked by wscript.exe or cscript.exe unless the terminal current directory 
fits the wildcard pattern '*\Health Service State\\*'

-------------------

### Possible causes of false positives

- Microsoft Operations Manager (MOM)
- Other scripts

-------------------
### References

- https://www.carbonblack.com/2017/03/15/attackers-leverage-excel-powershell-dns-latest-non-malware-attack/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
