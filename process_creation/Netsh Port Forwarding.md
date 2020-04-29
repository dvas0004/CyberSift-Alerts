# Netsh Port Forwarding
### Description

Detects netsh commands that configure a port forwarding

-------------------
### Severity

Medium

--------------

### Detailed Information

Triggers on command line instructions containing 'netsh interface portproxy add v4tov4 *'

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
