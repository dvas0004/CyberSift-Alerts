# Windows Processes Suspicious Parent Directory
### Description

Detect suspicious parent processes of well-known Windows processes

-------------------
### Severity

Low

-------------------

### Detailed Information

Triggers when one of the following processes run:

  - '*\svchost.exe'
  - '*\taskhost.exe'
  - '*\lsm.exe'
  - '*\lsass.exe'
  - '*\services.exe'
  - '*\lsaiso.exe'
  - '*\csrss.exe'
  - '*\wininit.exe'
  - '*\winlogon.exe'
 
 Unless run from:
  - '*\System32\\*'
  - '*\SysWOW64\\*'

-------------------

### Possible causes of false positives

- Some security products seem to spawn these

-------------------
### References

- https://securitybytes.io/blue-team-fundamentals-part-two-windows-processes-759fe15965e2
- https://www.carbonblack.com/2014/06/10/screenshot-demo-hunt-evil-faster-than-ever-with-carbon-black/
- https://www.13cubed.com/downloads/windows_process_genealogy_v2.pdf
- https://attack.mitre.org/techniques/T1036/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
