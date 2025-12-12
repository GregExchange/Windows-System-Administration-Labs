# Day 06 – System Health, Logs, and OS Repair

## Objectives
- Assess Windows system health
- Analyze system and application logs
- Repair operating system integrity issues

## Environment
- OS: Windows (VirtualBox VM)
- Network Mode: NAT

## Tools Used
- Event Viewer
- Command Prompt
- PowerShell

## Tasks Performed
- Reviewed system and application event logs
- Identified warning and error events
- Ran system file integrity checks
- Repaired Windows image using DISM

## Commands Used
```cmd
sfc /scannow
DISM /Online /Cleanup-Image /RestoreHealth

---

## STEP 3 — Commit the File

- Commit message:
- Commit directly to main
- Click **Commit changes**

---

## STEP 4 — PERFORM THE LAB IN YOUR WINDOWS VM (VERY IMPORTANT)

1. Open **Event Viewer**
 - Windows Logs → **System**
 - Windows Logs → **Application**
2. Look for:
 - Errors
 - Warnings
 - Critical events
3. Open **Command Prompt (Admin)** and run:
 ```cmd
 sfc /scannow
DISM /Online /Cleanup-Image /RestoreHealth
