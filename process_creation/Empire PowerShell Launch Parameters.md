# Empire PowerShell Launch Parameters
### Description

Detects suspicious powershell command line parameters used in Empire.

-------------------
### Severity

Critical

-------------------

### Detailed Information

Triggers on command line parameters:
  - * -NoP -sta -NonI -W Hidden -Enc *
  - * -noP -sta -w 1 -enc *

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://github.com/EmpireProject/Empire/blob/c2ba61ca8d2031dad0cfc1d5770ba723e8b710db/lib/common/helpers.py#L165

-https://github.com/EmpireProject/Empire/blob/e37fb2eef8ff8f5a0a689f1589f424906fe13055/lib/modules/powershell/persistence/powerbreach/deaduser.py#L191

- https://github.com/EmpireProject/Empire/blob/e37fb2eef8ff8f5a0a689f1589f424906fe13055/lib/modules/powershell/persistence/powerbreach/resolver.py#L178

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
