# LockerGoga Ransomware
### Description

Detects a command that clears the WMI trace log which indicates LockaerGoga ransomware activity.

-------------------
### Severity

- High

-------------------

### Detailed Information

Triggers on command line instructions containing:
  - \* cl Microsoft-Windows-WMI-Activity/Trace

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://abuse.io/lockergoga.txt

-------------------
### Supported Log Sources

- Windows Process Creation    

-------------------
