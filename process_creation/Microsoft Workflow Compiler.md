# Microsoft Workflow Compiler
### Description

Detects invocation of Microsoft Workflow Compiler, which may permit the execution of arbitrary unsigned code.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on launch of Microsoft.Workflow.Compiler.exe from anywhere in the filesystem.

-------------------

### Possible causes of false positives

- Legitimate MWC use (unlikely in modern enterprise environments)

-------------------
### References

- https://posts.specterops.io/arbitrary-unsigned-code-execution-vector-in-microsoft-workflow-compiler-exe-3d9294bc5efb

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
