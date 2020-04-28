# Execution in Webserver Root Folder
### Description

Detects a suspicious program execution in a web service root folder (filter out false positives).

-------------------
### Severity

Medium

-------------------

### Detailed Information

Triggers on execution from one of the following folders:
  - *\wwwroot\\*
  - *\wmpub\\*
  - *\htdocs\\*
  
Unless folder path also fits fitting the following:
  - *bin\\*
  - *\Tools\\*
  - *\SMSComponent\\*

-------------------

### Possible causes of false positives

- Various applications
- Tools that include ping or nslookup command invocations

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
