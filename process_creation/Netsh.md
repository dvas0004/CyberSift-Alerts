# Netsh
### Description

Allow Incoming Connections by Port or Application on Windows Firewall.

-------------------
### Severity

- Medium

-------------------

### Detailed Information

Triggers on command line instructions containing '* netsh firewall add *'

-------------------

### Possible causes of false positives

- Legitimate administration

-------------------
### References

- https://attack.mitre.org/software/S0246/ (Lazarus HARDRAIN)
- https://www.operationblockbuster.com/wp-content/uploads/2016/02/Operation-Blockbuster-RAT-and-Staging-Report.pdf

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
