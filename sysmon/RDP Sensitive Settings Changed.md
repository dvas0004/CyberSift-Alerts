# RDP Sensitive Settings Changed
### Description

Detects changes to RDP terminal service sensitive settings.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on sysmon event 'RegistryEvent (Value Set)' (Event ID 13) where TargetObject (ie: the registry key being set) fits one of:
  - '*\services\TermService\Parameters\ServiceDll*'
  - '*\Control\Terminal Server\fSingleSessionPerUser*'
  - '*\Control\Terminal Server\fDenyTSConnections*'


-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://blog.menasec.net/2019/02/threat-hunting-rdp-hijacking-via.html

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
