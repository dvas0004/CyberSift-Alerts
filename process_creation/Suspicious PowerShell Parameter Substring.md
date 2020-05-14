# Suspicious PowerShell Parameter Substring
### Description

Detects suspicious PowerShell invocation with a parameter substring

-------------------
### Severity

High

-------------------

### Detailed Information
Triggers on Powershell being invoked with a partial substring of a parameter in place of a parameter.
  - ' -windowstyle h '
  - ' -windowstyl h'
  - ' -windowsty h'
  - ' -windowst h'
  - ' -windows h'
  - ' -windo h'
  - ' -wind h'
  - ' -win h'
  - ' -wi h'
  - ' -win h '
  - ' -win hi '
  - ' -win hid '
  - ' -win hidd '
  - ' -win hidde '
  - ' -NoPr '
  - ' -NoPro '
  - ' -NoProf '
  - ' -NoProfi '
  - ' -NoProfil '
  - ' -nonin '
  - ' -nonint '
  - ' -noninte '
  - ' -noninter '
  - ' -nonintera '
  - ' -noninterac '
  - ' -noninteract '
  - ' -noninteracti '
  - ' -noninteractiv '
  - ' -ec '
  - ' -encodedComman '
  - ' -encodedComma '
  - ' -encodedComm '
  - ' -encodedCom '
  - ' -encodedCo '
  - ' -encodedC '
  - ' -encoded '
  - ' -encode '
  - ' -encod '
  - ' -enco '
  - ' -en '

-------------------

### Possible causes of false positives

- Penetration Tests

-------------------
### References

- http://www.danielbohannon.com/blog-1/2017/3/12/powershell-execution-argument-obfuscation-how-it-can-make-detection-easier

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
