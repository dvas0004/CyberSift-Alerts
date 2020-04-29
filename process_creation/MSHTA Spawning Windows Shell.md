# MSHTA Spawning Windows Shell
### Description

Detects a Windows command line executable started from MSHTA.

-------------------
### Severity

- High

-------------------

### Detailed Information

Triggers on mshta.exe launching one of the folowing executables:
  - '*\cmd.exe'
  - '*\powershell.exe'
  - '*\wscript.exe'
  - '*\cscript.exe'
  - '*\sh.exe'
  - '*\bash.exe'
  - '*\reg.exe'
  - '*\regsvr32.exe'
  - '*\BITSADMIN*'

-------------------

### Possible causes of false positives

- Printer software / driver installations
- HP software

-------------------
### References

- https://www.trustedsec.com/july-2015/malicious-htas/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
