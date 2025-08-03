

## Objective
This week focused on deepening understanding of system-level security controls and malware prevention techniques on macOS, using both CLI and GUI tools. Emphasis was placed on user access control, password policies, and native anti-malware protections.

## Tools Used
- Terminal
- VS Code
- macOS

# Week 4 Recap – Security Labs Part 2

## Objective
This week focused on deepening understanding of system-level security controls and malware prevention techniques on macOS, using both CLI and GUI tools. Emphasis was placed on user access control, password policies, and native anti-malware protections.

---

## Labs Completed

### ✅ Lab 1: User Accounts & Permissions
- Used `id`, `groups`, and `dscl` to explore user and group metadata in macOS
- Compared CLI results to GUI view in **System Settings > Users & Groups**
- Captured and stored GUI screenshot for documentation

### ✅ Lab 2: Password Policies & Expiration
- Ran `passwd` to test password change requirements
- Explored macOS GUI password management
- Discussed common enterprise password policy settings and their role in endpoint security

### ✅ Lab 3: macOS Anti-Malware
- Verified **Gatekeeper** status via `spctl --status`
- Documented behavior when opening unsigned apps (Gatekeeper GUI prompt)
- Investigated **XProtect** malware definitions and update logs via `system_profiler`
- Confirmed **MRT (Malware Removal Tool)** history using `MRTConfigData` in system update records
- Reviewed the definitions and types of malware (viruses, trojans, spyware, etc.) and how macOS mitigates them

---

## Reflections
- macOS includes strong native tools for threat prevention without third-party antivirus
- Understanding where user accounts, permissions, and policies live (CLI vs GUI) improves troubleshooting and auditing skills
- Apple has modernized malware handling using background frameworks instead of visible apps

---



