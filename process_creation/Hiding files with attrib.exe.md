# Hiding files with attrib.exe
### Description

Detects usage of attrib.exe to hide files from users.

-------------------
### Severity

- Low

-------------------

### Detailed Information

Triggers on:
  - attrib.exe run with +h parameter
 Unless:
  - It is run from a desktop.ini file
  - It is run from a .bat file within C:\\Windows\\system32\\*.bat

-------------------

### Possible causes of false positives

- igfxCUIService.exe hiding *.cui files via .bat script (attrib.exe a child of cmd.exe and igfxCUIService.exe is the parent of the cmd.exe)
- msiexec.exe hiding desktop.ini

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
