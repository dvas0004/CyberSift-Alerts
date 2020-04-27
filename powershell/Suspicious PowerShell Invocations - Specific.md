# Suspicious PowerShell Invocations - Specific
### Description

Detects suspicious PowerShell invocation command parameters.

-------------------
### Severity

- High

-------------------

### Detailed Information

Triggers on following Powershell command parameters:
  - ' -nop -w hidden -c * [Convert]::FromBase64String'
  - ' -w hidden -noni -nop -c "iex(New-Object'
  - ' -w hidden -ep bypass -Enc'
  - 'powershell.exe reg add HKCU\software\microsoft\windows\currentversion\run'
  - 'bypass -noprofile -windowstyle hidden (new-object system.net.webclient).download'
  - 'iex(New-Object Net.WebClient).Download'

-------------------

### Possible causes of false positives

- Penetration tests

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Powershell

-------------------
