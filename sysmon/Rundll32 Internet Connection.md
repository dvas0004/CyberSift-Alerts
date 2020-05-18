# Rundll32 Internet Connection
### Description

Detects a rundll32 that communicates with public IP addresses.

-------------------
### Severity

Medium

-------------------

### Detailed Information

Triggers on Sysmon event 'Network Connection' (ID 3) where connecting process ('Image' attribute in sysmon log) is rundll32.exe and Destination IP address ('DestinationIp') is not one of:
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
  - '127.*'

-------------------

### Possible causes of false positives

- Communication to other corporate systems that use IP addresses from public address spaces

-------------------
### References

- https://www.hybrid-analysis.com/sample/759fb4c0091a78c5ee035715afe3084686a8493f39014aea72dae36869de9ff6?environmentId=100

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
