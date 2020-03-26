# DHCP Server Error Failed Loading the CallOut DLL
### Description

This rule detects a DHCP server error in which a specified Callout DLL (in registry) could not be loaded.

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

- Joining a PC to a domain
- Large file upload
- Shared infrastructure (CDN)

-------------------
### References

- https://blog.3or.de/mimilib-dhcp-server-callout-dll-injection.html
- https://technet.microsoft.com/en-us/library/cc726884(v=ws.10).aspx
- https://msdn.microsoft.com/de-de/library/windows/desktop/aa363389(v=vs.85).aspx
    
-------------------
### Supported Log Sources

- windows dhcp

-------------------
