# MSHTA Suspicious Execution 01
### Description

Detection for mshta.exe suspicious execution patterns sometimes involving file polyglotism.

-------------------
### Severity

- High

-------------------

### Detailed Information

mshta.exe is used to execute "HTML Applications"; html documents with embedded scripts in VBScript or Javascript which may be used to execute commands in an environment where Powershell/cmd are disabled.
mshta.exe may thus be a sign of malicious code execution or lateral movement of an attacker.

-------------------
### Possible causes of false positives

- False positives depend on scripts and administrative tools used in the monitored environment

-------------------
### References

- None

-------------------
### Supported Log Sources

    - http://blog.sevagas.com/?Hacking-around-HTA-files
    - https://0x00sec.org/t/clientside-exploitation-in-2018-how-pentesting-has-changed/7356
    - https://docs.microsoft.com/en-us/dotnet/standard/data/xml/xslt-stylesheet-scripting-using-msxsl-script
    - https://medium.com/tsscyber/pentesting-and-hta-bypassing-powershell-constrained-language-mode-53a42856c997

-------------------
