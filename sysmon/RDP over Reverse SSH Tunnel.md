# RDP over Reverse SSH Tunnel
### Description

Detects svchost hosting RDP termsvcs communicating with the loopback address and on TCP port 3389.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on Sysmon event Network connection (ID 3) where connecting process is svchost.exe and source port is 3389 and Destination IP is '127.*.*.*' or '::1'.

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://twitter.com/SBousseaden/status/1096148422984384514

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
