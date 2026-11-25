# Mission 3 — Understand the operating system

> AI-assisted answer notes. Device and system values below were recorded in this session; private account details are omitted.

## 1. Task / objective
Describe operating-system functions and record privacy-safe system observations.

## 2. System observations

| Item | Observation |
|---|---|
| Operating system | macOS 27.0.1. Hardware model not recorded. |
| Python and Git | Python 3.14.7; Git 2.55.0. |
| Account identity | Omitted from this public report for privacy. |
| Storage | Root filesystem: approximately 926.3 GiB total, 12.7 GiB used, 751.5 GiB available in this session. |
| Running processes | No list obtained. macOS returned “operation not permitted” for process-list attempts. |

A process is a running instance of a program. A PID is the number the operating system assigns to distinguish one process from another.

## 3. Paths and permissions

An absolute path begins at the filesystem root. A relative path is interpreted from the current directory. Example relative path: mission-03-operating-system/README.md. For mission-02-terminal/terminal-practice/notes.txt, owner permissions were rw-: read and write, without execute permission. In permission letters, r means read, w means write, and x means execute or traverse.

## 4. Operating-system responsibilities

| Responsibility | What it does | Example |
|---|---|---|
| Process management | Starts programs, shares CPU time, stops programs. | Sharing CPU time between apps. |
| Memory management | Allocates RAM to programs and their active data. | Keeping browser tabs active. |
| Device management | Coordinates software and hardware through drivers and services. | Sending a print job. |
| File management | Organizes files and controls how they are stored and accessed. | Saving a document in a folder. |
| User interface and shell | Lets people control the computer through windows or commands. | Opening an app or running pwd. |
| Security and permissions | Controls access to files, accounts, and system resources. | Requiring permission to access protected data. |

## 5. Commands and tools recorded

sw_vers checked the macOS version; python3 --version and git --version checked software versions; storage was inspected for the root filesystem. Process-list commands were blocked by macOS permissions.

## 6. AI-assisted explanation

The operating system manages hardware resources and provides services that applications use. Processes are running programs; permissions determine which actions accounts and applications can perform.

## 7. Difficulty and resolution

The operating system blocked process-list access. No list is claimed and no security setting was changed.

## 8. Commit details

The Mission 3 folder was committed as “Document operating system and file management.” This factual update was committed separately on main as “Complete verified operating system observations.”

## 9. Evidence

Privacy-safe system values are recorded above. No account name, full device path, or process list is published.
