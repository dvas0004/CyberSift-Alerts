# PsExec Tool Execution
### Description

Detects PsExec service installation and execution events (service and Sysmon).

-------------------
### Severity

- Low

-------------------

### Detailed Information

Events:
  - 7045: A new service was installed in the system (Service Name: PSEXESVC, Service Path: *\PSEXESVC.exe)
  - 7037 Service enters the "running/stopped" state. (Service Name: PSEXESVC)

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://www.jpcert.or.jp/english/pub/sr/ir_research.html
- https://jpcertcc.github.io/ToolAnalysisResultSheet

-------------------
### Supported Log Sources

- windows process_creation

-------------------
