# AWMI Persistence - Command Line Event Consumer
### Description

Detects WMI command line event consumers.

-------------------
### Severity

High

-------------------

### Detailed Information
Triggers on sysmon event 'Image loaded' (event id 7) where 'Image' is 'C:\Windows\System32\wbem\WmiPrvSE.exe' and 'ImageLoaded' (ie: the DLL loaded by WmiPrvSE.exe) is 'wbemcons.dll'.  

-------------------

### Possible causes of false positives

- Unknown (data set is too small; further testing needed)

-------------------
### References

- https://www.eideon.com/2018-03-02-THL03-WMIBackdoors/

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
