# Processes created by MMC
### Description

Processes started by MMC could be a sign of lateral movement using MMC application COM object.

-------------------
### Severity

Medium

-------------------

### Detailed Information

Triggers on cmd.exe being launche as a child-process by mmc.exe and in turn used to run commands, unless that command is RunCmd.cmd

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://enigma0x3.net/2017/01/05/lateral-movement-using-the-mmc20-application-com-object/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
