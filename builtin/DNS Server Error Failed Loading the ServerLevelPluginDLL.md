# DNS Server Error Failed Loading the ServerLevelPluginDLL
### Description

This rule detects a DNS server error in which a specified plugin DLL (in registry) could not be loaded.

-------------------
### Severity

- Critical

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

- Unknown

-------------------
### References

- https://medium.com/@esnesenon/feature-not-bug-dnsadmin-to-dc-compromise-in-one-line-a0f779b8dc83
- https://technet.microsoft.com/en-us/library/cc735829(v=ws.10).aspx
- https://twitter.com/gentilkiwi/status/861641945944391680

-------------------
### Supported Log Sources

- windows DNS server

-------------------
