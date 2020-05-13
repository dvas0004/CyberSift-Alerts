# Suspicious Rundll32 Activity
### Description

Detects suspicious process related to rundll32 based on arguments.

-------------------
### Severity

Medium

-------------------

### Detailed Information
Triggers on process running fitting one of the following wildcard parameters:

  - '*\rundll32.exe* url.dll,*OpenURL *'
  - '*\rundll32.exe* url.dll,*OpenURLA *'
  - '*\rundll32.exe* url.dll,*FileProtocolHandler *'
  - '*\rundll32.exe* zipfldr.dll,*RouteTheCall *'
  - '*\rundll32.exe* Shell32.dll,*Control_RunDLL *'
  - '*\rundll32.exe javascript:*'
  - '* url.dll,*OpenURL *'
  - '* url.dll,*OpenURLA *'
  - '* url.dll,*FileProtocolHandler *'
  - '* zipfldr.dll,*RouteTheCall *'
  - '* Shell32.dll,*Control_RunDLL *'
  - '* javascript:*'
  - '*.RegisterXLL*'

-------------------

### Possible causes of false positives

- False positives depend on scripts and administrative tools used in the monitored environment

-------------------
### References

- http://www.hexacorn.com/blog/2017/05/01/running-programs-via-proxy-jumping-on-a-edr-bypass-trampoline/
- https://twitter.com/Hexacorn/status/885258886428725250
- https://gist.github.com/ryhanson/227229866af52e2d963cf941af135a52

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
