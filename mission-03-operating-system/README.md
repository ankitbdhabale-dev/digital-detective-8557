# Mission 3 — Understand the operating system


> AI-assisted answer notes. System values below were recorded in this session; no private account name or device identifiers are included.


## 1. Task / objective
Complete the tasks listed in this mission of the Digital Detective assignment.


## 2. Work completed and answer notes


## 3.1 System observations (must come from your computer)


| Information | What it tells you | Your privacy-safe observation |
|---|---|---|
| OS and system details | OS family/version and hardware/software environment | macOS 27.0.1. Python 3.14.7 and Git 2.55.0 were also available. Hardware model not recorded. |
| Current account identity | Which account is running the shell | The account name was not included in the public report for privacy. |
| Available and used storage | Disk capacity and space in use/free | For the root filesystem: approximately 926.3 GiB total, 12.7 GiB used, and 751.5 GiB available in this session. |
| System activity snapshot | Processes active at that moment | Not available: macOS denied both process-list attempts with “operation not permitted”; no process snapshot is claimed. |


A process is a running instance of a program. A PID (process identifier) is the number the operating system assigns to distinguish a process. Examples that may appear are a browser process and a text-editor process; report only ones you actually see.


## 3.3 Paths and permissions


An absolute path starts at the filesystem root and identifies a location independently of the current directory. A relative path is interpreted from the current directory. Examples: absolute `[REDACTED]/assignment/mission-03/README.md`; relative `mission-03-operating-system/README.md`. For `mission-02-terminal/terminal-practice/notes.txt`, owner permissions were `rw-` (read/write, not executable). In permission letters, `r` means read, `w` write, and `x` execute or traverse.


## 3.4 Operating-system responsibilities


| Responsibility | Explanation | Example |
|---|---|---|
| Process management | Starts programs, schedules their CPU time, and stops them. | Sharing CPU time between a browser and editor. |
| Memory management | Allocates RAM to programs and keeps their active data organized. | Giving a browser memory for open tabs. |
| Device management | Coordinates communication with hardware through drivers and system services. | Sending a print job to a printer. |
| File management | Organizes files and folders and controls how they are stored and accessed. | Saving a document into a chosen folder. |
| User interface / shell | Lets a person control the computer through windows, menus, or typed commands. | Opening an app or running `pwd` in Terminal. |
| Security and permissions | Controls access to accounts, files, and system resources. | Requiring permission before an app accesses protected data. |
