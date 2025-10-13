01_ResourceGroups/notes.md
# AZ-104 Lab: Manage Azure Resources – Resource Groups & Locks

## Lab Objective
Learn how to create and manage a Resource Group in Azure and apply locks to protect resources.

## Resource Group Creation
- Resource Group Name: `khem`
- Location: West US 
- Screenshot: ![Resource Group Created](01_ResourceGroups/Screenshots/rg.png)

## Azure Locks
- Applied **Read-only lock** to RG `khem`.
- Steps:
  1. Open RG → `khem`
  2. Click **Locks** → Add Lock → Type: Read-only
- Screenshot: ![Lock Applied](screenshots/rg_lock.png)

## Key Learnings
- Resource Groups organize resources.
- Locks prevent accidental deletion or modification.
- Azure Portal makes RG management easy.

