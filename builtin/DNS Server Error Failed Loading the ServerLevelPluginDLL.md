# DNS Server Error Failed Loading the ServerLevelPluginDLL
### Description

This rule detects a DNS server error in which a specified plugin DLL (in registry) could not be loaded.

-------------------
### Severity

- Critical

-------------------
### Detailed Information

Placing a malicious DLL on a network path which is accessible by one of the domain controllers’ computer accounts, dns.exe, which runs under SYSTEM can be made to load the DLL, and we thus can run code as SYSTEM on a domain controller, thus taking control of the domain.

-------------------
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
