# Windows Shell Spawning Suspicious Program
### Description

Detects a suspicious child process of a Windows shell.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on one of the following processes:

  - '*\schtasks.exe'
  - '*\nslookup.exe'
  - '*\certutil.exe'
  - '*\bitsadmin.exe'
  - '*\mshta.exe'

Running with one of the following parent processes (shells):

  - '*\mshta.exe'
  - '*\powershell.exe'
  - '*\cmd.exe'
  - '*\rundll32.exe'
  - '*\cscript.exe'
  - '*\wscript.exe'
  - '*\wmiprvse.exe'

Unless running from the directory: '*\ccmcache\*'

-------------------

### Possible causes of false positives

- Administrative scripts
- Microsoft SCCM

-------------------
### References

- https://mgreen27.github.io/posts/2018/04/02/DownloadCradle.html

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
