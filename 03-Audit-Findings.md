# IT Audit Findings Report – CyberBank

## Overview
This document summarizes key audit findings identified during IT General Controls (ITGC) testing at CyberBank Demo Environment.

---

## Finding 1: Weak Access Control

**Condition:**
Users were found to have excessive privileges beyond their job requirements.

**Criteria:**
Access should be granted based on least privilege principle.

**Cause:**
Lack of Role-Based Access Control (RBAC).

**Effect:**
Increased risk of unauthorized access to sensitive systems and data.

**Risk Level:**
High

**Recommendation:**
Implement Role-Based Access Control (RBAC) and conduct periodic access reviews.

---

## Finding 2: Lack of Multi-Factor Authentication

**Condition:**
Authentication relies only on username and password.

**Criteria:**
MFA should be enforced for secure authentication.

**Cause:**
MFA not implemented in the system.

**Effect:**
High risk of credential theft and unauthorized access.

**Risk Level:**
High

**Recommendation:**
Enable Multi-Factor Authentication for all users.

---

## Finding 3: No Backup Mechanism

**Condition:**
No evidence of backup processes or backup logs.

**Criteria:**
Regular backups must be performed and tested.

**Cause:**
No defined backup policy.

**Effect:**
Risk of permanent data loss in case of failure or ransomware attack.

**Risk Level:**
High

**Recommendation:**
Implement automated and encrypted backup solution with regular testing.

---

## Summary

The audit identified significant weaknesses in access control, authentication, and backup processes.

These deficiencies expose CyberBank to high operational and security risks and require immediate remediation.
