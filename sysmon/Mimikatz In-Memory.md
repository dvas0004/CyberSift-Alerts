# Mimikatz In-Memory
### Description

Detects certain DLL loads when Mimikatz gets executed

-------------------
### Severity

Medium

-------------------
### Detailed Information

DLLS:
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
