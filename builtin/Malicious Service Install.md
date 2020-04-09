# Malicious Service Install
### Description

This method detects well-known keywords of malicious services in the Windows System Eventlog.

-------------------
### Severity

- High

-------------------
### Detailed Information
On Windows Event ID: 7045 (Installation of Services); rule triggers on services with names: 

  -'WCESERVICE'
  -'WCE SERVICE'
  -'pwdump*'
  -'gsecdump*'
  -'cachedump*'

or having filenames:
  -'*\PAExec*'
  -'winexesvc.exe*'
  -'*\DumpSvc.exe'
  -'mssecsvc2.0'
  -'* net user *'

-------------------

### Possible causes of false positives

-Unknown, unlikely

-------------------
### References

-None

-------------------
### Supported Log Sources

- windows security

-------------------
