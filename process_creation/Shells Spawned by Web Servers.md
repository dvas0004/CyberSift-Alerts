# Shells Spawned by Web Servers
### Description

Web servers that spawn shell processes could be the result of a successfully placed web shell or an other attack.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on one of:
  - cmd.exe
  - sh.exe
  - bash.exe
  - powershell.exe

Being run with one of:
  - w3wp.exe
  - httpd.exe
  - nginx.exe
  - php-cgi.exe

-------------------

### Possible causes of false positives

- Particular web applications may spawn a shell process legitimately

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
