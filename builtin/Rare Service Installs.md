# Rare Service Installs
### Description

Detects rare service installs that only appear a few times per time frame and could reveal password dumpers, backdoor installs or other types of malicious services. 

-------------------

### Severity

- Low

-------------------

### Detailed Information

Events:
  - 7045 New Service Was Installed

Service with rare filename was installed more than 5 times in a 7 day period.

-------------------

### Possible causes of false positives

- Software installation
- Software updates

-------------------
### References

- None
-------------------
### Supported Log Sources

- windows system

-------------------
