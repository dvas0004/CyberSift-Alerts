# Net.exe Execution
### Description

Detects execution of Net.exe, whether suspicious or benign.

-------------------
### Severity

Low

-------------------

### Detailed Information

Triggers on calling of net.exe or net1.exe with one of the following parameters:
  - '* group*'
  - '* localgroup*'
  - '* user*'
  - '* view*'
  - '* share'
  - '* accounts*'
  - '* use*'

-------------------

### Possible causes of false positives

- Will need to be tuned. If using Splunk, I recommend | stats count by Computer,CommandLine following the search for easy hunting by computer/CommandLine.

-------------------
### References

- https://pentest.blog/windows-privilege-escalation-methods-for-pentesters/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
