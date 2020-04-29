# IIS Native-Code Module Command Line Installation
### Description

Detects suspicious IIS native-code module installations via command line.

-------------------
### Severity

Medium

-------------------

### Detailed Information

Triggers on command line instructions:
  - \*\APPCMD.EXE install module /name:*

-------------------

### Possible causes of false positives

- Unknown as it may vary from organisation to arganisation how admins use to install IIS modules

-------------------
### References

- https://researchcenter.paloaltonetworks.com/2018/01/unit42-oilrig-uses-rgdoor-iis-backdoor-targets-middle-east/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
