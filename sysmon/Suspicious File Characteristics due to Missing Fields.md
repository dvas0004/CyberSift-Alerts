# Suspicious File Characteristics due to Missing Fields
### Description

Detects Executables without FileVersion,Description,Product,Company likely created with py2exe.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on Sysmon event having Description field: '\?' and one or more of (field: value):
  - Product: '\?'
  - FileVersion: '\?'
  - Company: '\?'

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://securelist.com/muddywater/88059/
- https://www.virustotal.com/#/file/276a765a10f98cda1a38d3a31e7483585ca3722ecad19d784441293acf1b7beb/detection

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
