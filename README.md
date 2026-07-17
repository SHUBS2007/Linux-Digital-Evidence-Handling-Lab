# Linux-Based Digital Evidence Handling and Investigation Lab

## Project Overview

This project simulates the initial phase of a digital forensic investigation using Kali Linux. The objective was to understand how investigators organize digital evidence, search for suspicious information, preserve evidence integrity, and document the investigation process using standard Linux commands.

This project was created as part of my cybersecurity learning journey and focuses on practical Linux skills used in digital investigations.

---

## Investigation Scenario

A computer belonging to a suspected cybercrime participant was seized for investigation.

The objective of the investigation was to:

- Organize digital evidence
- Search for suspicious information
- Preserve evidence integrity
- Create backup copies
- Generate cryptographic hashes
- Document the investigation process

---

## Project Objectives

- Learn Linux file system navigation
- Create a structured investigation workspace
- Organize digital evidence
- Search evidence using Linux commands
- Protect evidence using file permissions
- Create backup archives
- Verify evidence integrity using SHA-256
- Generate an investigation report

---

## Technologies Used

- Kali Linux
- Linux Terminal
- GNU Nano
- SHA-256
- TAR Archive Utility

---

## Project Structure

```text
Digital-Investigation-Lab
│
├── Backup
│   └── chat.txt
│
├── Evidence
│   ├── chat.txt
│   ├── recovered_passwords.txt
│   └── suspicious_ip.txt
│
├── Logs
│
├── Reports
│   └── investigation_report.txt
│
├── screenshots
│
└── evidence_backup.tar.gz
```

---

## Investigation Workflow

### Phase 1 – Investigation Workspace

Created the directory structure:

- Evidence
- Logs
- Reports
- Backup

Created sample evidence files.

---

### Phase 2 – Evidence Analysis

Performed investigation using:

- find
- grep
- cat
- ls -l

Searched for suspicious keywords and verified evidence.

---

### Phase 3 – Evidence Preservation

Protected evidence using:

- chmod

Created backup using:

- cp

Archived evidence using:

- tar

Generated SHA-256 hash for integrity verification.

---

## SHA-256 Hash

```
713b4604c978da6ca411e45e67417cc908847834b5349c790f195068b19a2
```

The hash acts as a digital fingerprint of the evidence. Any modification to the file changes the hash value, making it useful for integrity verification.

---

## Linux Commands Used

| Command | Purpose |
|----------|---------|
| pwd | Display current directory |
| ls | List files |
| mkdir | Create directories |
| cd | Navigate directories |
| touch | Create files |
| nano | Edit files |
| cat | View file contents |
| find | Locate evidence |
| grep | Search keywords |
| chmod | Protect evidence |
| cp | Create backup |
| mv | Rename evidence |
| tar | Archive evidence |
| sha256sum | Verify integrity |

---

## Skills Learned

- Linux File Management
- Digital Evidence Handling
- Evidence Preservation
- SHA-256 Hashing
- Linux Terminal
- Basic Digital Forensics
- Documentation

---

## Future Improvements

- Log Analysis
- User Activity Investigation
- Bash Automation
- Memory Forensics
- File Timeline Analysis
- Integration with Autopsy

---

## Author

**Shubham Bhatti**

B.Tech Cybersecurity Student

Marwadi University

GitHub: https://github.com/SHUBS2007

LinkedIn: https://linkedin.com/in/shubham-bhatti2007

---

**This project was created for educational purposes to demonstrate Linux-based digital evidence handling and investigation techniques.**
