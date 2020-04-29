# MavInject Process Injection
### Description

Detects process injection using the signed Windows tool Mavinject32.exe

-------------------
### Severity

- Critical

-------------------

### Detailed Information

Triggers on /INJECTRUNNING detected in a command line instruction

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://twitter.com/gN3mes1s/status/941315826107510784
- https://reaqta.com/2017/12/mavinject-microsoft-injector/
- https://twitter.com/Hexacorn/status/776122138063409152

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
