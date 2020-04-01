# Microsoft Workflow Compiler
### Description

Detects invocation of Microsoft Workflow Compiler, which may permit the execution of arbitrary unsigned code.

-------------------
### Severity

High

-------------------
<!---
### Detailed Information

- Why is this alert triggered?
- What are the typical causes that generate this alert? (e.g. port scans, unusual file access activity, etc...)
- Which corroborating information should be looked up?
- Any supporting queries to get more information?
- Any supporting visualizations to get more information?

-------------------
--->
### Possible causes of false positives

- Legitimate MWC use (unlikely in modern enterprise environments)

-------------------
### References

- https://posts.specterops.io/arbitrary-unsigned-code-execution-vector-in-microsoft-workflow-compiler-exe-3d9294bc5efb

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
