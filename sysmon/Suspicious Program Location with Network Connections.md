# Suspicious Program Location with Network Connections
### Description

Detects programs with network connections running in suspicious files system locations.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on Sysmon Event Network connection (ID 3) where connecting process is powershell.exe and Destination IP is:
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

- Unknown

-------------------
### References

- https://docs.google.com/spreadsheets/d/17pSTDNpa0sf6pHeRhusvWG6rThciE8CsXTSlDUAZDyo

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
