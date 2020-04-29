# Microsoft Office Product Spawning Windows Shell
### Description

Detects a Windows command line executable started from Microsoft Word, Excel, Powerpoint, Publisher and Visio.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on one of the following processes:
  - '*\cmd.exe'
  - '*\powershell.exe'
  - '*\wscript.exe'
  - '*\cscript.exe'
  - '*\sh.exe'
  - '*\bash.exe'
  - '*\scrcons.exe'
  - '*\schtasks.exe'
  - '*\regsvr32.exe'
  - '*\hh.exe'
  - '*\wmic.exe'
  - '*\mshta.exe'
  - '*\rundll32.exe'
  - '*\msiexec.exe'
  - '*\forfiles.exe'
  - '*\scriptrunner.exe'
  - '*\mftrace.exe'
  - '*\AppVLP.exe'
  - '*\svchost.exe'
  
Being launched from one of the following parent processes:
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

- https://www.hybrid-analysis.com/sample/465aabe132ccb949e75b8ab9c5bda36d80cf2fd503d52b8bad54e295f28bbc21?environmentId=100
- https://mgreen27.github.io/posts/2018/04/02/DownloadCradle.html

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
