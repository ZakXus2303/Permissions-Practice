# Linux Permissions & Access Control Lab (SOC-Focused)

## Overview
This project demonstrates fundamental Linux permission management and access control concepts relevant to a SOC Analyst role. The lab focuses on enforcing least privilege, validating access boundaries, and verifying permissions using standard Linux tools.

The objective was not to memorise commands, but to understand **why** permissions exist and **how** misconfigurations can impact system security.

---

## Skills Demonstrated
- Linux user and group management
- Filesystem permissions (chmod, chown)
- Least privilege enforcement
- Permission validation and testing
- SOC-relevant access control concepts

---

## Environment
- Ubuntu Linux (Virtual Machine)
- Bash shell
- No external automation tools used

---

## Project Structure

---

## Lab Objectives
- Create a shared directory in a system-level location
- Assign controlled ownership using users and groups
- Restrict access using Linux permissions
- Test access as a non-admin SOC user
- Verify that permissions prevent unauthorised actions

---

## Key Concepts Covered
- **Least Privilege**: Users are granted only the permissions required
- **Access Control**: Linux enforces security boundaries at the filesystem level
- **SOC Relevance**: Analysts often read logs and artifacts without modifying system files
- **Verification**: Permissions must be tested, not assumed

---

## Commands Used
A full list of commands is available in:
- `commands-used.md`

Detailed explanations and reasoning are documented in:
- `permissions-explained.md`

---

## Why This Matters for SOC Analysts
In real-world environments:
- SOC analysts frequently access `/var` and `/var/log`
- Write access to system directories can cause incidents
- Improper permissions can lead to data loss or compromise

This lab demonstrates how Linux prevents these risks when configured correctly.

---

## Reflection
This project strengthened my understanding of Linux filesystem permissions and reinforced the importance of validating access controls. It also highlighted how expected failures (permission denied) confirm that security mechanisms are working as intended.

---

## Next Steps
- Log analysis and awareness
- File integrity and monitoring concepts
- Continued SOC-focused labs and practice

