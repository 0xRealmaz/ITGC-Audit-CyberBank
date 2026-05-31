# ITGC Control Testing – CyberBank Demo Environment

## Overview
This document presents the results of testing key IT General Controls (ITGC) within CyberBank Demo Environment.

---

## Control Testing Results

| Control Area | Control Objective | Test Procedure | Result | Evidence | Finding | Risk Level | Recommendation |
|--------------|------------------|----------------|--------|----------|---------|------------|----------------|

| Access Management | Ensure only authorized users have access | Review user access permissions | Failed | Users with excessive privileges found | Lack of least privilege enforcement | High | Implement RBAC and least privilege model |
| Authentication | Ensure secure login mechanism | Check MFA implementation | Failed | MFA not enabled | Weak authentication controls | High | Enable Multi-Factor Authentication |
| Change Management | Ensure all system changes are approved | Review change tickets and approvals | Partial | Missing approval documentation | Uncontrolled system changes | Medium | Implement formal change approval process |
| Backup & Recovery | Ensure data can be restored | Verify backup logs and schedule | Failed | No backup evidence found | No backup strategy in place | High | Implement automated backup solution |
| Logging & Monitoring | Ensure system activity is tracked | Check logging/SIEM configuration | Failed | No logs or SIEM configured | No visibility of security events | High | Deploy centralized logging and SIEM solution |

---

## Summary of Testing

The control testing revealed multiple deficiencies across all ITGC domains, particularly in access control, authentication, and monitoring.

These weaknesses expose CyberBank to significant operational and security risks.
