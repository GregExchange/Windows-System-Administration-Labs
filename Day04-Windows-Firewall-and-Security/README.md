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
