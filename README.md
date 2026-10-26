# Windows System Information & Health Report

## Project Overview
A beginner-level IT project using built-in Windows tools and PowerShell to collect system information and review basic hardware health indicators.

## Objectives
- Identify the Windows edition and system architecture.
- Collect processor and memory information.
- Review storage usage and system uptime.
- Generate a Windows battery report.
- Document findings professionally.

## Tools Used
- Windows PowerShell
- Get-ComputerInfo
- Get-CimInstance
- Get-PSDrive
- powercfg batteryreport
- Windows Task Manager

## Key Findings
- Operating system: Windows 10 Home, version 2009, 64-bit.
- Processor: AMD Ryzen 5 8640HS with Radeon 760M Graphics.
- Processor configuration: 6 cores and 12 logical processors.
- Installed memory: 8 GB, verified in Task Manager.
- C: drive free space: approximately 69.45 GB at the time of testing.
- Battery design capacity: 68,000 mWh.
- Battery full charge capacity: 66,030 mWh.
- Estimated battery capacity relative to design: approximately 97.1%.

## Project Files

- [View System Health Findings](findings.txt) — system specifications, storage information, uptime, and assessment notes.
- [View Battery Report](battery-report.html) — Windows-generated battery usage and capacity information.

**Privacy note:** Review the battery report for personal or device-identifying information before sharing it publicly.
## Limitations
These findings represent measurements collected at the time of testing. Battery capacity is an estimate and does not independently establish overall battery health. The project does not certify hardware condition or Windows security status.

## Scope
All checks were performed on my own Windows PC. The project uses built-in diagnostic tools and does not intentionally modify system settings.


## Lessons Learned

- How to collect Windows system information using PowerShell and built-in tools.
- How to identify processor specifications, memory, and storage availability.
- How to retrieve system uptime and review basic system information.
- How to generate and interpret a Windows battery report.
- How to calculate battery full-charge capacity relative to its original design capacity.
- Why system measurements should be documented with dates and clear limitations.
- How to organize technical findings into a professional GitHub portfolio project.
