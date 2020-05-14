# Suspicious Control Panel DLL Load
### Description

Detects suspicious Rundll32 execution from control.exe as used by Equation Group and Exploit Kits.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on rundll32.exe being run by \System32\control.exe, unless it's used to load Shell32.dll.

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://twitter.com/rikvduijn/status/853251879320662017

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
