# NetNTLM Downgrade Attack
### Description

Detects post exploitation using NetNTLM downgrade attacks.

-------------------
### Severity

- Critical

-------------------

### Detailed Information

LM password hashes are trivial to crack; they are therefore disabled on modern Windows systems (2000 onwards) but may still be usable by malicious attackers using a downgrade attack. 

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://www.optiv.com/blog/post-exploitation-using-netntlm-downgrade-attacks

-------------------
### Supported Log Sources

- windows sysmon

-------------------
