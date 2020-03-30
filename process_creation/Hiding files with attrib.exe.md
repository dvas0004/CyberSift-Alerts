# Hiding files with attrib.exe
### Description

Detects usage of attrib.exe to hide files from users.

-------------------
### Severity

- Low

-------------------
<!---
### Detailed Information

- Why is this alert triggered?
- What are the typical causes that generate this alert? (e.g. port scans, unusual file access activity, etc...)
- Which corroborating information should be looked up?
- Any supporting queries to get more information?
- Any supporting visualizations to get more information?

-------------------
--->
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
