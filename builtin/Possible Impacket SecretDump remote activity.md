# Possible Impacket SecretDump remote activity
### Description

Detect AD credential dumping using impacket secretdump HKTL.

-------------------
### Severity

- High

-------------------

### Detailed Information

Triggers on event id 5145 (request for access to Active Directory share), with accessed share having name fitting the following wildcard string:
'\\*\ADMIN$'
And the accessed file being: 'SYSTEM32\*.tmp'

-------------------

### Possible causes of false positives

  - Pentesting

-------------------
### References

  - https://blog.menasec.net/2019/02/threat-huting-10-impacketsecretdump.html
  
-------------------
### Supported Log Sources

- windows security

-------------------
