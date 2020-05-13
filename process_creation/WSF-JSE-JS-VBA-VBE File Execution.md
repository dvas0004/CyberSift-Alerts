# WSF/JSE/JS/VBA/VBE File Execution
### Description

Detects suspicious file execution by wscript and cscript.

-------------------
### Severity

Medium

-------------------

### Detailed Information

Triggers on :
  - '*\wscript.exe'
  - '*\cscript.exe'

Run on one of the following script types:
  - '*.jse'
  - '*.vbe'
  - '*.js'
  - '*.vba'

-------------------

### Possible causes of false positives

- Will need to be tuned. I recommend adding the user profile path in CommandLine if it is getting too noisy.

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
