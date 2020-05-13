# Executable used by PlugX in Uncommon Location - Sysmon Version
### Description

Detects the execution of an executable that is typically used by PlugX for DLL side loading started from an uncommon location

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on running of the following executables, except when run from certain directories:

  - '*\CamMute.exe' Unless executed from: '*\Lenovo\Communication Utility\\*'
  - '*\chrome_frame_helper.exe' Unless executed from: '*\Google\Chrome\application\\*'
  - '*\dvcemumanager.exe' Unless executed from: '*\Microsoft Device Emulator\\*'
  - '*\Gadget.exe' Unless executed from: '*\Windows Media Player\\*'
  - '*\hcc.exe' Unless executed from: '*\HTML Help Workshop\\*'
  - '*\hkcmd.exe' Unless executed from: '*\System32\\*', '*\SysNative\\*', '*\SysWow64\\*'
  - '*\Mc.exe' Unless executed from: '*\Microsoft Visual Studio*', '*\Microsoft SDK*', '*\Windows Kit*'
  - '*\MsMpEng.exe' Unless executed from: '*\Microsoft Security Client\\*', '*\Windows Defender\\*', '*\AntiMalware\\*'
  - '*\msseces.exe' Unless executed from: '*\Microsoft Security Center\\*', '*\Microsoft Security Client\\*', '*\Microsoft      Security Essentials\\*'
  - '*\OInfoP11.exe' Unless executed from: '*\Common Files\Microsoft Shared\\*'
  - '*\OleView.exe' Unless executed from: '*\Microsoft Visual Studio*', '*\Microsoft SDK*', '*\Windows Kit*', '*\Windows Resource Kit\\*'
  - '*\rc.exe' Unless executed from: '*\Microsoft Visual Studio*', '*\Microsoft SDK*', '*\Windows Kit*', '*\Windows Resource Kit\\*', '*\Microsoft.NET\\*'
-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- http://www.hexacorn.com/blog/2016/03/10/beyond-good-ol-run-key-part-36/
- https://countuponsecurity.com/2017/06/07/threat-hunting-in-the-enterprise-with-appcompatprocessor/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
