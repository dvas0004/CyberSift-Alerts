# DHCP Server Error Failed Loading the CallOut DLL
### Description

This rule detects a DHCP server error in which a specified Callout DLL (in registry) could not be loaded.

-------------------
### Severity

- Critical

-------------------

### Detailed Information

Microsoft DHCP Server takes the following steps in loading third-party DLLs:
1. Microsoft DHCP Server checks the previously defined registry location for the presence of third-party DLLs.
2. If no registry entries are found, the DHCP Server internal hook table remains empty, and no DHCP Server event notifications are sent.
3. If one or more registry entries is found, Microsoft DHCP Server reads the first registry entry, in alphabetical order, and attempts to load the corresponding third-party DLL. If the DLL loads successfully, Microsoft DHCP Server ceases checking for additional third-party DLLs.
4. Microsoft DHCP Server calls the DhcpServerCalloutEntry function in the loaded third-party DLL, retrieving the associated DHCP_CALLOUT_TABLE function and thereby determining which events initiate notification to the third-party DLL. Notification comes in the form of corresponding third-party functions: one or more of which can be included in the third-party DLL, and each of which are defined in the following DHCP Server API reference pages.

This event is fired if, on step 3 the DLL fails to load.

-------------------

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
