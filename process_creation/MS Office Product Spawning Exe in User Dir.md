# MS Office Product Spawning Exe in User Dir
### Description

Detects an executable in the users directory started from Microsoft Word, Excel, Powerpoint, Publisher or Visio

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on an executable being run from the C:\\users directory by one of the following parent processes:

  - '*\WINWORD.EXE'
  - '*\EXCEL.EXE'
  - '*\POWERPNT.exe'
  - '*\MSPUB.exe'
  - '*\VISIO.exe'
  - '*\OUTLOOK.EXE'

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- sha256=23160972c6ae07f740800fa28e421a81d7c0ca5d5cab95bc082b4a986fbac57c
- https://blog.morphisec.com/fin7-not-finished-morphisec-spots-new-campaign

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
