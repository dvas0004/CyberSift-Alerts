# CobaltStrike Process Injection
### Description

Detects a possible remote threat creation with certain characteristics which are typical for Cobalt Strike beacons.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on a Create Remote Thread event where the target process in which thread is to be created has a memory address ending in (0x) 0D80

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://medium.com/@olafhartong/cobalt-strike-remote-threads-detection-206372d11d0f

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
