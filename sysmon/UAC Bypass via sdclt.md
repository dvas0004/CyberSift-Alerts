# UAC Bypass via sdclt
### Description

Detects changes to HKCU:\Software\Classes\exefile\shell\runas\command\isolatedCommand .

-------------------
### Severity

High

-------------------
### Detailed Information

Triggers on Sysmon event ID 13 (RegistryEvent) where TargetObject attribute fits:
  - 'HKEY_USERS\\*\Classes\exefile\shell\runas\command\isolatedCommand'

-------------------
### Possible causes of false positives

- Unknown

-------------------
### References

- https://enigma0x3.net/2017/03/17/fileless-uac-bypass-using-sdclt-exe/

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
