# DNS ServerLevelPluginDll Install
### Description

Detects the installation of a plugin DLL via ServerLevelPluginDll parameter in Registry, 
which can be used to execute code in context of the DNS server (restart required)

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on \services\DNS\Parameters\ServerLevelPluginDll registry value being set.

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://medium.com/@esnesenon/feature-not-bug-dnsadmin-to-dc-compromise-in-one-line-a0f779b8dc83

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
