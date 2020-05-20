# Malicious Named Pipe
### Description

Detects the creation of a named pipe used by known APT malware.

-------------------
### Severity

Critical

-------------------
### Detailed Information
Triggers on Sysmon events 'Pipe created' (event id 17) and 'Pipe connected' (event id 18).
Triggers on creation on one of the following Named Pipes ('NamedPipe' attribute):
         - '\isapi_http'  # Uroburos Malware Named Pipe
         - '\isapi_dg'  # Uroburos Malware Named Pipe
         - '\isapi_dg2'  # Uroburos Malware Named Pipe
         - '\sdlrpc'  # Cobra Trojan Named Pipe http://goo.gl/8rOZUX
         - '\ahexec'  # Sofacy group malware
         - '\winsession'  # Wild Neutron APT malware https://goo.gl/pivRZJ
         - '\lsassw'  # Wild Neutron APT malware https://goo.gl/pivRZJ
         - '\46a676ab7f179e511e30dd2dc41bd388'  # Project Sauron https://goo.gl/eFoP4A
         - '\9f81f59bc58452127884ce513865ed20'  # Project Sauron https://goo.gl/eFoP4A
         - '\e710f28d59aa529d6792ca6ff0ca1b34'  # Project Sauron https://goo.gl/eFoP4A
         - '\rpchlp_3'  # Project Sauron https://goo.gl/eFoP4A - Technical Analysis Input
         - '\NamePipe_MoreWindows'  # Cloud Hopper Annex B https://www.pwc.co.uk/cyber-security/pdf/cloud-hopper-annex-b-final.pdf, US-CERT Alert - RedLeaves https://www.us-cert.gov/ncas/alerts/TA17-117A
         - '\pcheap_reuse'  # Pipe used by Equation Group malware 77486bb828dba77099785feda0ca1d4f33ad0d39b672190079c508b3feb21fb0
         - '\msagent_*'  # CS default named pipes https://github.com/Neo23x0/sigma/issues/253
         # - '\status_*'  # CS default named pipes https://github.com/Neo23x0/sigma/issues/253

-------------------
### Possible causes of false positives

- Unknown

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
