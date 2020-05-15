# DHCP Callout DLL installation
### Description

Detects the installation of a Callout DLL via CalloutDlls and CalloutEnabled parameter in Registry, 
which can be used to execute code in context of the DHCP server (restart required)

-------------------
### Severity

High

-------------------

### Detailed Information
Triggers on setting of one of the following registry keys:
  - \Services\DHCPServer\Parameters\CalloutDlls
  - \Services\DHCPServer\Parameters\CalloutEnabled

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://blog.3or.de/mimilib-dhcp-server-callout-dll-injection.html
- https://technet.microsoft.com/en-us/library/cc726884(v=ws.10).aspx
- https://msdn.microsoft.com/de-de/library/windows/desktop/aa363389(v=vs.85).aspx

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
