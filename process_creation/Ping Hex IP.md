# Ping Hex IP
### Description

Detects a ping command that uses a hex encoded IP address.

-------------------
### Severity

High

-------------------
<!---
### Detailed Information

- Why is this alert triggered?
- What are the typical causes that generate this alert? (e.g. port scans, unusual file access activity, etc...)
- Which corroborating information should be looked up?
- Any supporting queries to get more information?
- Any supporting visualizations to get more information?

-------------------
--->
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
