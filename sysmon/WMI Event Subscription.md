# WMI Event Subscription
### Description

Detects creation of WMI event subscription persistence method.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on one or more of the following sysmon events:
  - 19 WmiFilterEvent
  - 20 WmiEventConsumer
  - 21 WmiBindingEvent
  
-------------------

### Possible causes of false positives

- exclude legitimate (vetted) use of WMI event subscription in your network

-------------------
### References

- https://attack.mitre.org/techniques/T1084/

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
