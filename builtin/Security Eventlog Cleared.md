# Security Eventlog Cleared
### Description

Some threat groups tend to delete the local 'Security' Eventlog using certain utitlities.

-------------------
### Severity

- High

-------------------

### Detailed Information

Events:
  - 517 The audit log was cleared.
  - 1102 The audit log was cleared.

Triggers when security event log is cleared.

-------------------

### Possible causes of false positives

- Rollout of log collection agents (the setup routine often includes a reset of the local Eventlog)
- System provisioning (system reset before the golden image creation)

-------------------
### References

- None
-------------------
### Supported Log Sources

- windows security

-------------------
