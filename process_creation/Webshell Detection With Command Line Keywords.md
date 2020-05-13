# Webshell Detection With Command Line Keywords
### Description

Detects certain command line parameters often used during reconnaissance activity via web shells.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on one of the following commands being run:
  - whoami
  - net user
  - ping -n
  - systeminfo
 
 From one of the following parent processes (web shells):
  - '*\apache*'
  - '*\tomcat*'
  - '*\w3wp.exe'
  - '*\php-cgi.exe'
  - '*\nginx.exe'
  - '*\httpd.exe'
  

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
