# Registry Persistence via Explorer Run Key
### Description

Detects a possible persistence mechanism using RUN key for Windows Explorer and poiting to a suspicious folder.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on Sysmon event RegistryEvent (Value Set) (ID 13) where 'TargetObject' event attribute (the Registry key being set) fits the wildcard pattern: '*\Microsoft\Windows\CurrentVersion\Policies\Explorer\Run' and the 'Details' attribute (The Registry value being set) fits one of:
  - 'C:\Windows\Temp\\*'
  - 'C:\ProgramData\\*'
  - '*\AppData\\*'
  - 'C:\$Recycle.bin\\*'
  - 'C:\Temp\\*'
  - 'C:\Users\Public\\*'
  - 'C:\Users\Default\\*'


-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://researchcenter.paloaltonetworks.com/2018/07/unit42-upatre-continues-evolve-new-anti-analysis-techniques/

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
