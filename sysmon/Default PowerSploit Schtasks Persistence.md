# Default PowerSploit Schtasks Persistence
### Description

Detects the creation of a schtask via PowerSploit Default Configuration.

-------------------
### Severity

High

-------------------

### Detailed Information
Triggers on powershell commands fitting one of the following wildcard patterns:
  - '*\schtasks.exe*/Create*/RU*system*/SC*ONLOGON*'
  - '*\schtasks.exe*/Create*/RU*system*/SC*DAILY*'
  - '*\schtasks.exe*/Create*/RU*system*/SC*ONIDLE*'
  - '*\schtasks.exe*/Create*/RU*system*/SC*HOURLY*'

-------------------

### Possible causes of false positives

- False positives are possible, depends on organisation and processes

-------------------
### References

- https://github.com/0xdeadbeefJERKY/PowerSploit/blob/8690399ef70d2cad10213575ac67e8fa90ddf7c3/Persistence/Persistence.psm1

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
