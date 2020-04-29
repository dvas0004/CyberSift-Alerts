# Netsh RDP Port Forwarding
### Description

Detects netsh commands that configure a port forwarding of port 3389 used for RDP

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on detecting commands fitting the format: 'netsh i\* p\*=3389 c\*'

-------------------

### Possible causes of false positives

- Legitimate administration

-------------------
### References

- https://www.fireeye.com/blog/threat-research/2019/01/bypassing-network-restrictions-through-rdp-tunneling.html

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
