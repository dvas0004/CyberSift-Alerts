# Malicious PowerShell Keywords
### Description

Detects keywords from well-known PowerShell exploitation frameworks.

-------------------
### Severity

- High

-------------------

### Detailed Information

Triggers on the following Powershell commands:

  - AdjustTokenPrivileges
  - IMAGE_NT_OPTIONAL_HDR64_MAGIC
  - Microsoft.Win32.UnsafeNativeMethods
  - ReadProcessMemory.Invoke
  - SE_PRIVILEGE_ENABLED
  - LSA_UNICODE_STRING
  - MiniDumpWriteDump
  - PAGE_EXECUTE_READ
  - SECURITY_DELEGATION
  - TOKEN_ADJUST_PRIVILEGES
  - TOKEN_ALL_ACCESS
  - TOKEN_ASSIGN_PRIMARY
  - TOKEN_DUPLICATE
  - TOKEN_ELEVATION
  - TOKEN_IMPERSONATE
  - TOKEN_INFORMATION_CLASS
  - TOKEN_PRIVILEGES
  - TOKEN_QUERY
  - Metasploit
  - Mimikatz

-------------------

### Possible causes of false positives

- Penetration Tests

-------------------
### References

- https://adsecurity.org/?p=2921

-------------------
### Supported Log Sources

- Windows Powershell

-------------------
