# Suspicious PowerShell Download
### Description

Detects suspicious PowerShell download command.

-------------------
### Severity

- Medium

-------------------

### Detailed Information

Triggers on Keywords:
  - 'System.Net.WebClient).DownloadString('
  - 'system.net.webclient).downloadfile('

-------------------

### Possible causes of false positives

- PowerShell scripts that download content from the Internet

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Powershell

-------------------
