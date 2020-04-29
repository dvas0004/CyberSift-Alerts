# MsiExec Web Install
### Description

Detects suspicious msiexec process starts with web addreses as parameter.

-------------------
### Severity

Medium

-------------------

### Detailed Information

Triggers on command line instructions containing '\* msiexec*:\/\/*'

-------------------

### Possible causes of false positives

- False positives depend on scripts and administrative tools used in the monitored environment

-------------------
### References

- https://blog.trendmicro.com/trendlabs-security-intelligence/attack-using-windows-installer-msiexec-exe-leads-lokibot/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
