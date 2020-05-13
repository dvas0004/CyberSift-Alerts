# Sysprep on AppData Folder
### Description

Detects suspicious sysprep process start with AppData folder as target 
(as used by Trojan Syndicasec in Thrip report by Symantec)

-------------------
### Severity

Medium

-------------------

### Detailed Information
Triggers on process 
  - '*\sysprep.exe
  
Running with folder fitting *\AppData\\* as target.


-------------------

### Possible causes of false positives

- False positives depend on scripts and administrative tools used in the monitored environment

-------------------
### References

    - https://www.symantec.com/blogs/threat-intelligence/thrip-hits-satellite-telecoms-defense-targets
    - https://app.any.run/tasks/61a296bb-81ad-4fee-955f-3b399f4aaf4b

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
