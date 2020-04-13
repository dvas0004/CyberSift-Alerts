# Password Change on Directory Service Restore Mode (DSRM) Account
### Description

The Directory Service Restore Mode (DSRM) account is a local administrator account on Domain Controllers. Attackers may change the password to gain persistence.

-------------------
### Severity

- High

-------------------

### Detailed Information

Triggered on Event 4794, which fires on changing of a DSRM password.

-------------------
### Possible causes of false positives

- Initial installation of a domain controller

-------------------
### References

- https://adsecurity.org/?p=1714

-------------------
### Supported Log Sources

- windows security

-------------------
