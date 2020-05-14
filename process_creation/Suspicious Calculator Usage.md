# Suspicious Calculator Usage
### Description

Detects suspicious use of calc.exe with command line parameters or in a suspicious directory, which is likely caused by some PoC or detection evasion

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on calc.exe being run from any directory with command line parameters or from any directory other than System32 or SysWOW64

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://twitter.com/ItsReallyNick/status/1094080242686312448

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
