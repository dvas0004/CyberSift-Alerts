# Suspicious Process Creation
### Description

Detects suspicious process starts on Windows systems based on keywords.

-------------------
### Severity

Medium

-------------------

### Detailed Information

Triggers on commandlines fitting one of the following wildcard patterns:

  - vssadmin.exe delete shadows*
  - vssadmin delete shadows*
  - vssadmin create shadow /for=C:*
  - copy \\?\GLOBALROOT\Device\\*\windows\ntds\ntds.dit*
  - copy \\?\GLOBALROOT\Device\\*\config\SAM*
  - reg SAVE HKLM\SYSTEM *
  - reg SAVE HKLM\SAM *
  - '* sekurlsa:*'
  - net localgroup adminstrators * /add
  - net group "Domain Admins" * /ADD /DOMAIN
  - certutil.exe *-urlcache* http*
  - certutil.exe *-urlcache* ftp*
  - netsh advfirewall firewall *\AppData\\*
  - attrib +S +H +R *\AppData\\*
  - schtasks* /create *\AppData\\*
  - schtasks* /sc minute*
  - '*\Regasm.exe *\AppData\\*'
  - '*\Regasm *\AppData\\*'
  - '*\bitsadmin* /transfer*'
  - '*\certutil.exe * -decode *'
  - '*\certutil.exe * -decodehex *'
  - '*\certutil.exe -ping *'
  - icacls * /grant Everyone:F /T /C /Q
  - '* wmic shadowcopy delete *'
  - '* wbadmin.exe delete catalog -quiet*'
  - '*\wscript.exe *.jse'
  - '*\wscript.exe *.js'
  - '*\wscript.exe *.vba'
  - '*\wscript.exe *.vbe'
  - '*\cscript.exe *.jse'
  - '*\cscript.exe *.js'
  - '*\cscript.exe *.vba'
  - '*\cscript.exe *.vbe'
  - '*\fodhelper.exe'
  - '*waitfor*/s*'
  - '*waitfor*/si persist*'
  - '*remote*/s*'
  - '*remote*/c*'
  - '*remote*/q*'
  - '*AddInProcess*'
  - '* /stext *'
  - '* /scomma *'
  - '* /stab *'
  - '* /stabular *'
  - '* /shtml *'
  - '* /sverhtml *'
  - '* /sxml *'

-------------------

### Possible causes of false positives

- False positives depend on scripts and administrative tools used in the monitored environment

-------------------
### References

- https://www.swordshield.com/2015/07/getting-hashes-from-ntds-dit-file/
- https://www.youtube.com/watch?v=H3t_kHQG1Js&feature=youtu.be&t=15m35s
- https://winscripting.blog/2017/05/12/first-entry-welcome-and-uac-bypass/
- https://twitter.com/subTee/status/872244674609676288
- https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/remote-tool-examples
- https://tyranidslair.blogspot.ca/2017/07/dg-on-windows-10-s-executing-arbitrary.html
- https://www.trustedsec.com/2017/07/new-tool-release-nps_payload/
- https://subt0x10.blogspot.ca/2017/04/bypassing-application-whitelisting.html
- https://gist.github.com/subTee/7937a8ef07409715f15b84781e180c46#file-rat-bat
- https://twitter.com/vector_sec/status/896049052642533376
- http://security-research.dyndns.org/pub/slides/FIRST-TC-2018/FIRST-TC-2018_Tom-Ueltschi_Sysmon_PUBLIC.pdf

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
