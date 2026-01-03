# Day 03 – Network Configuration and Troubleshooting

## Objectives
- Understand Windows network configuration
- Verify IP addressing and DNS resolution
- Troubleshoot common connectivity issues

## Environment
- OS: Windows (VirtualBox VM)
- Network Mode: NAT

## Commands Used
```cmd
ipconfig /all
ping 8.8.8.8
ping google.com
tracert google.com
nslookup google.com

---

## STEP 3 — Commit the File

- Commit message:
- Commit directly to main
- Click **Commit changes**

---

## STEP 4 — DO THE ACTUAL LAB IN YOUR VM (IMPORTANT)

On your **Windows VM**, open **Command Prompt** and run:

```cmd
ipconfig /all
ping 8.8.8.8
ping google.com
tracert google.com
nslookup google.com
# Day 03 – Network Configuration & Troubleshooting (Windows)

## Objective
Verify and troubleshoot network connectivity inside a Windows 11 VirtualBox VM.

## Environment
- OS: Windows 11 Home (25H2)
- VM Platform: VirtualBox (NAT networking)
- IPv4 Subnet: 10.0.2.0/24

## Tasks Completed
- Identified network adapter configuration
- Verified IP addressing using ipconfig /all
- Tested connectivity:
  - Loopback (127.0.0.1)
  - Default Gateway (10.0.2.2)
  - External IP (8.8.8.8)
- Verified DNS resolution using nslookup
- Captured firewall profile status

## Evidence
- Output file: `day03-network.txt`
- Screenshot:
  - ipconfig /all (PowerShell)

## Result
All network connectivity and DNS tests completed successfully.
