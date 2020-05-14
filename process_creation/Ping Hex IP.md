# Ping Hex IP
### Description

Detects a ping command that uses a hex encoded IP address.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on ping or ping.exe run with a parameter starting with '0x'

-------------------

### Possible causes of false positives

- Unlikely, because no sane admin pings IP addresses in a hexadecimal form

-------------------
### References

- https://github.com/vysec/Aggressor-VYSEC/blob/master/ping.cna
- https://twitter.com/vysecurity/status/977198418354491392

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
