# RDP Login From Localhost
### Description

RDP login with localhost source address may be a tunnelled login

-------------------
### Severity

- High

-------------------

### Detailed Information

Events:
  - 5156: Windows Filtering Platform has allowed a connection.

Source Port: 3389

Destination Port: 3389

Source Addresses:
  - '127.*'
  - '::1'

Destination Addresses:
  - '127.*'
  - '::1'
  
-------------------

### Possible causes of false positives

-Unknown

-------------------
### References

- https://www.fireeye.com/blog/threat-research/2019/01/bypassing-network-restrictions-through-rdp-tunneling.html

-------------------
### Supported Log Sources

- windows security

-------------------
