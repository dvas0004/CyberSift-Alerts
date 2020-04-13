# Password Dumper Activity on LSASS
### Description

Detects process handle on LSASS process with certain access mask and object type SAM_DOMAIN.

-------------------
### Severity

High

-------------------
### Detailed Information

Alert triggers on lsass.exe opening an object handle with object type SAM_DOMAIN with 0x705.

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://twitter.com/jackcr/status/807385668833968128

-------------------
### Supported Log Sources

- windows security

-------------------
