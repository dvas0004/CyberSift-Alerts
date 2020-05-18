# Suspicious Scripting in a WMI Consumer
### Description

Detects suspicious scripting in WMI Event Consumers 

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on Sysmon Event WmiEventConsumer activity detected (ID 20) where Destination field fits one of:
  - '*new-object system.net.webclient).downloadstring(*'
  - '*new-object system.net.webclient).downloadfile(*'
  - '*new-object net.webclient).downloadstring(*'
  - '*new-object net.webclient).downloadfile(*'
  - '* iex(*'
  - '*WScript.shell*'
  - '* -nop *'
  - '* -noprofile *'
  - '* -decode *'
  - '* -enc *'

-------------------

### Possible causes of false positives

- Administrative scripts

-------------------
### References

- https://in.security/an-intro-into-abusing-and-identifying-wmi-event-subscriptions-for-persistence/
- https://github.com/Neo23x0/signature-base/blob/master/yara/gen_susp_lnk_files.yar#L19

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
