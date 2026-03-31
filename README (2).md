
# Open-Source Audit: LibreOffice on  Ubuntu 22.04 LTS

**Student Name:** Naman Mehta</br>
**Roll Number:** 24BAI10885  </br>
**Course:** Open-Source Software  </br>
**Date:** March 2026

## Chosen Software
LibreOffice — A free and open-source office suite, developed by The Document Foundation.

## System Details
- Distribution: Ubuntu 22.04 LTS
-  Kernel: 5.15.0-91-generic
- LibreOffice Version: 7.5.4.2

## File Structure
GitHub Repository Structure
```bash
oss-audit-24BAI10885/
├── README.md
├── oss-audit-24BAI10885
├── scripts/
│   ├── script1_system_identity.sh
│   ├── script2_package_inspector.sh
│   ├── script3_disk_auditor.sh
│   ├── script4_log_analyzer.sh
│   └── script5_manifesto_generator.sh
└── screenshots/
    ├── script1_run.png
    ├── script2_run.png
    ├── script3_run.png
    ├── script4_run.png
    └── script5_run.png
```


## Scripts Description

| Script | Purpose | Key Concepts |
|--------|---------|--------------|
| script1_system_identity.sh | System information report | Variables, command substitution |
| script2_package_inspector.sh | Check LibreOffice installation | rpm queries, case statements |
| script3_disk_auditor.sh | Directory permissions audit | For loops, arrays, permissions |
| script4_log_analyzer.sh | Log file error analysis | While read loops, grep, counters |
| script5_manifesto_generator.sh | Interactive philosophy generator | User input, file writing |

## How to Run

### Prerequisites
- Ubuntu 22.04 LTS (or any Linux distribution with Bash)
-  LibreOffice installed (sudo apt install libreoffice)

### Run Scripts
```bash
# Make scripts executable
chmod +x scripts/*.sh

# Run each script
./scripts/script1_system_identity.sh
./scripts/script2_package_inspector.sh
./scripts/script3_disk_auditor.sh
./scripts/script4_log_analyzer.sh /var/log/messages
./scripts/script5_manifesto_generator.sh
```

## Dependencies
-	bash (built-in)
-	apt (Ubuntu 22.04 LTS/RHEL package manager)
-	grep, awk, cut (standard Unix utilities)
  
## Notes
All scripts are tested on Ubuntu 22.04 LTS. For other distributions, adjust package manager commands.
This completes the full LibreOffice Audit project for Ubuntu 22.04 LTS. All scripts are ready to run, and the report provides comprehensive coverage of the origin story, license analysis, ethical reflections, Linux footprint, ecosystem mapping, and comparison with proprietary alternatives.
