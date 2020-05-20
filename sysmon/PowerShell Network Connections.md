# PowerShell Network Connections
### Description

Detects a Powershell process that opens network connections - check for suspicious target ports and target systems - adjust to your environment (e.g. extend filters with company's ip range')  

-------------------
### Severity

Low

-------------------

### Detailed Information

Triggers on Sysmon event 'Network connection' (Event ID 3), where 'SourceImage' (ie: the process making the connection) is powershell.exe where the 'DestinationIp' is NOT one of:
  - '10.*'
  - '192.168.*'
  - '172.16.*'
  - '172.17.*'
  - '172.18.*'
  - '172.19.*'
  - '172.20.*'
  - '172.21.*'
  - '172.22.*'
  - '172.23.*'
  - '172.24.*'
  - '172.25.*'
  - '172.26.*'
  - '172.27.*'
  - '172.28.*'
  - '172.29.*'
  - '172.30.*'
  - '172.31.*'
  - '127.0.0.1'

-------------------

### Possible causes of false positives

- Administrative scripts

-------------------
### References

- https://www.youtube.com/watch?v=DLtJTxMWZ2o

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
