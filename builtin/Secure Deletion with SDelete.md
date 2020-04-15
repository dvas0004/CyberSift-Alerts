# Secure Deletion with SDelete
### Description

Detects renaming of file while deletion with SDelete tool.

-------------------
### Severity

- Medium

-------------------

### Detailed Information

EventID:
  - 4656 A handle to an object was requested.
  - 4663 An attempt was made to access an object
  - 4658 The handle to an object was closed

Triggers when file is renamed to:
  - '*.AAA'
  - '*.ZZZ'

-------------------

### Possible causes of false positives

- Legitime usage of SDelete

-------------------
### References

- https://jpcertcc.github.io/ToolAnalysisResultSheet
- https://www.jpcert.or.jp/english/pub/sr/ir_research.html
- https://technet.microsoft.com/en-us/en-en/sysinternals/sdelete.aspx

-------------------
### Supported Log Sources

- windows security

-------------------
