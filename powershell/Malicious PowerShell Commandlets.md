# Malicious PowerShell Commandlets
### Description

Detects Commandlet names from well-known PowerShell exploitation frameworks.

-------------------
### Severity

- High

-------------------

### Detailed Information

Triggers on the following Powershell keywords:

  - Invoke-DllInjection
  - Invoke-Shellcode
  - Invoke-WmiCommand
  - Get-GPPPassword
  - Get-Keystrokes
  - Get-TimedScreenshot
  - Get-VaultCredential
  - Invoke-CredentialInjection
  - Invoke-Mimikatz
  - Invoke-NinjaCopy
  - Invoke-TokenManipulation
  - Out-Minidump
  - VolumeShadowCopyTools
  - Invoke-ReflectivePEInjection
  - Invoke-UserHunter
  - Find-GPOLocation
  - Invoke-ACLScanner
  - Invoke-DowngradeAccount
  - Get-ServiceUnquoted
  - Get-ServiceFilePermission
  - Get-ServicePermission
  - Invoke-ServiceAbuse
  - Install-ServiceBinary
  - Get-RegAutoLogon
  - Get-VulnAutoRun
  - Get-VulnSchTask
  - Get-UnattendedInstallFile
  - Get-ApplicationHost
  - Get-RegAlwaysInstallElevated
  - Get-Unconstrained
  - Add-RegBackdoor
  - Add-ScrnSaveBackdoor
  - Gupt-Backdoor
  - Invoke-ADSBackdoor
  - Enabled-DuplicateToken
  - Invoke-PsUaCme
  - Remove-Update
  - Check-VM
  - Get-LSASecret
  - Get-PassHashes
  - Show-TargetScreen
  - Port-Scan
  - Invoke-PoshRatHttp
  - Invoke-PowerShellTCP
  - Invoke-PowerShellWMI
  - Add-Exfiltration
  - Add-Persistence
  - Do-Exfiltration
  - Start-CaptureServer
  - Get-ChromeDump
  - Get-ClipboardContents
  - Get-FoxDump
  - Get-IndexedItem
  - Get-Screenshot
  - Invoke-Inveigh
  - Invoke-NetRipper
  - Invoke-EgressCheck
  - Invoke-PostExfil
  - Invoke-PSInject
  - Invoke-RunAs
  - MailRaider
  - New-HoneyHash
  - Set-MacAttribute
  - Invoke-DCSync
  - Invoke-PowerDump
  - Exploit-Jboss
  - Invoke-ThunderStruck
  - Invoke-VoiceTroll
  - Set-Wallpaper
  - Invoke-InveighRelay
  - Invoke-PsExec
  - Invoke-SSHCommand
  - Get-SecurityPackages
  - Install-SSP
  - Invoke-BackdoorLNK
  - PowerBreach
  - Get-SiteListPassword
  - Get-System
  - Invoke-BypassUAC
  - Invoke-Tater
  - Invoke-WScriptBypassUAC
  - PowerUp
  - PowerView
  - Get-RickAstley
  - Find-Fruit
  - HTTP-Login
  - Find-TrustedDocuments
  - Invoke-Paranoia
  - Invoke-WinEnum
  - Invoke-ARPScan
  - Invoke-PortScan
  - Invoke-ReverseDNSLookup
  - Invoke-SMBScanner
  - Invoke-Mimikittenz

-------------------

### Possible causes of false positives

- Penetration testing

-------------------
### References

- https://adsecurity.org/?p=2921

-------------------
### Supported Log Sources

- Windows Powershell

-------------------
