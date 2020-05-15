# Executable in ADS
### Description

Detects the creation of an ADS data stream that contains an executable (non-empty imphash).

-------------------
### Severity

Critical

-------------------
### Detailed Information

Triggers on creation of a file stream containing an executable.
The rule identifies whether the stream contains an executable or not by applying imphash (hash of imports inside PE header of executable) to the contents of the filestream. If imphash is not '00000000000000000000000000000000' (null imphash) the rule does not trigger.

-------------------
### Possible causes of false positives

- Unknown

-------------------
### References

- https://twitter.com/0xrawsec/status/1002478725605273600?s=21

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
