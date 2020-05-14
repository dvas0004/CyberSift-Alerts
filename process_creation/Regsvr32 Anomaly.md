# Regsvr32 Anomaly
### Description

Detects various anomalies in relation to regsvr32.exe

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers where: 
  - regsvr32.exe is run from a directory fitting \*\\Temp\\\*
  - with powershell.exe as parent process.
  - wscript.exe is run with regsvr32.exe as parent process
  - regsvr32.exe is used to install scrobj.dll from an http or ftp server
  - regsvr32.exe is run from commandline with excel.exe as parent process
-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://subt0x10.blogspot.de/2017/04/bypass-application-whitelisting-script.html

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
