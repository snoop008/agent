---
name: autosar-c-security-review
description: >
  Review AUTOSAR Classic C code for security
  vulnerabilities involving memory safety,
  concurrency, cryptography, communication,
  and security-relevant state machines.
---

# AUTOSAR Classic C Security Review

Perform a read-only, evidence-based security review.

1. Identify the module and its AUTOSAR interfaces.
2. Determine the target compiler and relevant configuration.
3. Identify external inputs and trust boundaries.
4. Trace security-relevant data and control flow.
5. Analyze memory safety and integer operations.
6. Check concurrent access and asynchronous callbacks.
7. Review cryptographic operations and key lifecycle.
8. Review security state transitions and error handling.
9. Validate suspected vulnerabilities using available evidence.
10. Report actionable findings with CWE references.

For every finding, provide:
- Source file and line
- Vulnerability description
- Potential security impact
- Evidence supporting the finding
- Confidence level
- Recommended mitigation
- Suggested verification test

Do not claim that a vulnerability is confirmed
unless the available evidence supports that conclusion.

Do not automatically modify source code.
