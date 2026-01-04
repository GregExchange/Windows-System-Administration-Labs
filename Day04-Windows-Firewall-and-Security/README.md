# Day 04 – Windows Firewall & Security
Day04/
 ├─ README.md
 ├─ day04-firewall.txt
 ├─ firewall-profiles.png
 ├─ defender-status.png
 └─ ping-test.png

## Objective
Inspect and validate Windows Defender Firewall and security status on a Windows 11 VM.

## Environment
- OS: Windows 11 Home (25H2)
- VM: VirtualBox (NAT networking)

## Tasks Completed
- Verified firewall profiles (Domain, Private, Public)
- Reviewed inbound firewall rules
- Confirmed Windows Defender status
- Tested outbound connectivity
- Verified firewall service is running

## Evidence
- Output file: day04-firewall.txt
- Screenshots:
  - firewall-profiles.png
  - defender-status.png
  - ping-test.png

## Result
Windows Defender Firewall and security services are enabled and functioning correctly.
# Day 04 – Windows Firewall and Basic Security

## Objectives
- Understand Windows Firewall functionality
- Create and manage firewall rules
- Troubleshoot blocked network traffic

## Environment
- OS: Windows (VirtualBox VM)
- Network Mode: NAT

## Tools Used
- Windows Defender Firewall
- Command Prompt
- Event Viewer

## Tasks Performed
- Reviewed existing firewall profiles
- Created inbound firewall rule to block ICMP
- Tested connectivity before and after rule enforcement
- Identified blocked traffic behavior
- Restored normal connectivity

## Commands Used
```cmd
ping 8.8.8.8
ping google.com

---

## STEP 3 — Commit the File

- Commit message:
- Commit directly to main
- Click **Commit changes**

---

## STEP 4 — PERFORM THE LAB IN YOUR WINDOWS VM

1. Open **Windows Defender Firewall**
2. Go to **Advanced Settings**
3. Create **Inbound Rule**
 - Type: Custom (or ICMP if available)
 - Action: Block
 - Protocol: ICMPv4
4. Test:
 ```cmd
 ping 8.8.8.8
