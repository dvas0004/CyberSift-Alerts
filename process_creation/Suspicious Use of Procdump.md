# Suspicious Use of Procdump
### Description

Detects suspicious uses of the SysInternals Procdump utility.

-------------------
### Severity

Medium

-------------------

### Detailed Information

Detects suspicious uses of the SysInternals Procdump utility by using a special command line parameter in combination with the lsass.exe process. This way we're also able to catch cases in which the attacker has renamed the procdump executable.
Triggers on command line instructions fitting the wildcard patterns:
  - '* -ma *'
  - '* lsass.exe*'

-------------------

### Possible causes of false positives

- Unlikely, because no one should dump an lsass process memory
- Another tool that uses the command line switches of Procdump

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
