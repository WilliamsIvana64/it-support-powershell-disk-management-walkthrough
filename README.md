# IT Support PowerShell Disk Management Walkthrough

## Project Summary
This project demonstrates a basic IT support workflow using PowerShell to safely inspect disk and volume information on a Windows system. The goal is to simulate a real-world troubleshooting scenario where an IT support technician gathers system information without making configuration changes.

### Languages Used
- PowerShell

### Environment
- Windows 10

### Tools and Technologies
- PowerShell
- Windows Disk Management utilities

---

## Demonstration
PowerShell was used to inspect disk and volume information on a Windows system. The `Get-Disk` command displayed all connected disks and their status. The `Get-Volume` command was used to identify drive letters, file system types, and available storage. These commands reflect common IT support diagnostic practices.

---

## Media
*(Screenshots will be added here)*

---

## Actions and Observations
- `Get-Disk` confirmed that all system disks were online and accessible.
- `Get-Volume` displayed available storage and file system details.
- No changes were made to disk configuration, ensuring system stability.

---

## Lessons Learned
This project reinforced the importance of using read-only PowerShell commands during system diagnostics and demonstrated how command-line tools support safe troubleshooting in IT environments.
