# Mimikatz In-Memory
### Description

Detects certain DLL loads when Mimikatz gets executed

-------------------
### Severity

Medium

-------------------
### Detailed Information
Triggers on Sysmon event 'Image loaded' (event id 7) where rundll32.exe loads one of:
  - vaultcli.dll
  - wlanapi.dll
  and not one of:
  - 'ntdsapi.dll'
  - 'netapi32.dll'
  - 'imm32.dll'
  - 'samlib.dll'
  - 'combase.dll'
  - 'srvcli.dll'
  - 'shcore.dll'
  - 'ntasn1.dll'
  - 'cryptdll.dll'
  - 'logoncli.dll'

Within a 30 second timeframe.

-------------------
### Possible causes of false positives

- Unknown

-------------------
### References

- https://securityriskadvisors.com/blog/post/detecting-in-memory-mimikatz/

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
