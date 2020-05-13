# WScript or CScript Dropper
### Description

Detects wscript/cscript executions of scripts located in user directories.

-------------------
### Severity

- High

-------------------

### Detailed Information

Triggers on:
  - '*\wscript.exe'
  - '*\cscript.exe'

Running with one of the following command line parameters:
  - '* C:\Users\\*.jse *'
  - '* C:\Users\\*.vbe *'
  - '* C:\Users\\*.js *'
  - '* C:\Users\\*.vba *'
  - '* C:\Users\\*.vbs *'
  - '* C:\ProgramData\\*.jse *'
  - '* C:\ProgramData\\*.vbe *'
  - '* C:\ProgramData\\*.js *'
  - '* C:\ProgramData\\*.vba *'
  - '* C:\ProgramData\\*.vbs *'

-------------------

### Possible causes of false positives

- Winzip
- Other self-extractors

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
