# Security Support Provider (SSP) added to LSA configuration
### Description

Detects the addition of a SSP to the registry. Upon a reboot or API call, SSP DLLs gain access to encrypted and plaintext passwords stored in Windows. 

-------------------
### Severity

Critical

-------------------

### Detailed Information

Triggers on Sysmon Event RegistryEvent (Value Set) (ID 13) where 'TargetObject' has one of the following values:
  - 'HKLM\System\CurrentControlSet\Control\Lsa\Security Packages'
  - 'HKLM\System\CurrentControlSet\Control\Lsa\OSConfig\Security Packages'

And where 'Image' (process from which events originates)
  - Image: C:\Windows\system32\msiexec.exe
  - Image: C:\Windows\syswow64\MsiExec.exe

-------------------

### Possible causes of false positives

- Unlikely

-------------------
### References

- https://attack.mitre.org/techniques/T1101/
- https://powersploit.readthedocs.io/en/latest/Persistence/Install-SSP/

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
