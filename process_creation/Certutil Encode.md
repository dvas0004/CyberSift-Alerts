# Certutil Encode
### Description

Detects suspicious a certutil command that used to encode files, which is sometimes used for data exfiltration.

-------------------
### Severity

Medium

-------------------

### Detailed Information

Triggers on Command Line Instructions:
  - certutil -f -encode *
  - certutil.exe -f -encode *
  - certutil -encode -f *
  - certutil.exe -encode -f *

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/certutil
- https://unit42.paloaltonetworks.com/new-babyshark-malware-targets-u-s-national-security-think-tanks/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
