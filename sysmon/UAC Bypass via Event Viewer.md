# UAC Bypass via Event Viewer
### Description

Detects UAC bypass method using Windows event viewer.

-------------------
### Severity

Critical

-------------------

### Detailed Information

Triggers on: 
  - Sysmon Event RegistryEvent (Event ID 13) where TargetObject value fits: 'HKEY_USERS\\*\mscfile\shell\open\command'
  - Sysmon Event Process creation (Event ID 1) where Parent process is eventvwr.exe and process name is not mmc.exe

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://enigma0x3.net/2016/08/15/fileless-uac-bypass-using-eventvwr-exe-and-registry-hijacking/
- https://www.hybrid-analysis.com/sample/e122bc8bf291f15cab182a5d2d27b8db1e7019e4e96bb5cdbd1dfe7446f3f51f?environmentId=100

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
