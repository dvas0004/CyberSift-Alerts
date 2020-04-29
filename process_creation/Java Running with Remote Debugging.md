# Java Running with Remote Debugging
### Description

Detects a JAVA process running with remote debugging allowing more than just localhost to connect.

-------------------
### Severity

Medium

-------------------

### Detailed Information

Triggers on command line instructions containing \*transport=dt_socket,address=\*

unless the value of 'address' is:
  - 127.0.0.1
  - localhost

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
