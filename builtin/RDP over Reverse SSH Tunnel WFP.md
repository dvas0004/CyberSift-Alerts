# RDP over Reverse SSH Tunnel WFP
### Description

Detects svchost hosting RDP termsvcs communicating with the loopback address and on TCP port 3389

-------------------
### Severity

- High

-------------------

### Detailed Information

Windows Event ID:
  - 5156 Windows Filtering Platform Allowed A Connection Through

Source Port:
  - 3389

Source Address:
  - 127.*
  - ::1
  
-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://twitter.com/SBousseaden/status/1096148422984384514

-------------------
### Supported Log Sources

- windows security

-------------------
