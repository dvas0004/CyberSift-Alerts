# Taskmgr as Parent
### Description

Detects the creation of a process from Windows task manager.

-------------------
### Severity

Low

-------------------

### Detailed Information

Triggers when a process is run with taskmgr.exe as parent process.
Does not trigger if the created child process is resmon.exe and mmc.exe

-------------------

### Possible causes of false positives

- Administrative activity

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
