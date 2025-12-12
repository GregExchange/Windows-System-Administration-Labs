# Day 09 – NTFS Permissions and Access Control

## Objectives
- Configure NTFS permissions on folders
- Apply least privilege access principles
- Verify user access based on group membership

## Environment
- OS: Windows (VirtualBox VM)
- Network Mode: NAT

## Tools Used
- File Explorer
- Security (NTFS) Permissions
- Local Users and Groups

## Tasks Performed
- Created shared data folders
- Applied NTFS permissions to folders
- Assigned permissions based on group membership
- Tested access using different user accounts

## Folder Structure
C:\CorpData\
├── Accounting
├── IT

## Permissions Applied
- Accounting folder:
  - Finance group: Modify
  - Helpdesk group: Read
- IT folder:
  - Helpdesk group: Modify
  - Finance group: Read

## Results
- Permissions applied successfully
- Unauthorized access prevented
- Authorized access confirmed

## Observations
- NTFS permissions enforce data security
- Group-based permissions simplify access management
- Least privilege reduces risk of data exposure
Add Day 09 NTFS permissions and access control lab
C:\CorpData\Accounting
C:\CorpData\IT

