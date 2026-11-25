# Mission 3 — Understand the operating system

> Draft based on the assignment. Replace observation and reflection prompts with your own verified work and rewrite explanations in your own words before submission. Do not claim GitHub actions until they are actually visible.

## 1. Task / objective
Complete the tasks listed in this mission of the Digital Detective assignment.

## 2. Work completed and answer notes

## 3.1 System observations (must come from your computer)

| Information | What it tells you | Your privacy-safe observation |
|---|---|---|
| OS and system details | OS family/version and hardware/software environment | [RUN `sw_vers` on macOS, `systeminfo` on Windows, or `uname -a` on Linux; redact device identifiers] |
| Current account identity | Which account is running the shell | [Use `whoami`; replace the actual username with `[redacted]` in submitted evidence] |
| Available and used storage | Disk capacity and space in use/free | [RUN `df -h` on macOS/Linux or check Settings on Windows; do not include personal volume names] |
| System activity snapshot | Processes active at that moment | [Use Activity Monitor / Task Manager or `top`; report general examples only, no identifying details] |

A process is a running instance of a program. A PID (process identifier) is the number the operating system assigns to distinguish a process. Examples that may appear are a browser process and a text-editor process; report only ones you actually see.

## 3.3 Paths and permissions

An absolute path starts at the filesystem root and identifies a location independently of the current directory. A relative path is interpreted from the current directory. Examples: absolute `[REDACTED]/assignment/mission-03/README.md`; relative `mission-03/README.md` (replace with a real example from your project). In a permission string, `r` allows reading, `w` allows changing contents, and `x` allows running a file or traversing a directory. [Record the owner permission letters from a file in your practice folder; do not change permissions.]

## 3.4 Operating-system responsibilities

| Responsibility | Explanation | Example |
|---|---|---|
| Process management | Starts programs, schedules their CPU time, and stops them. | Sharing CPU time between a browser and editor. |
| Memory management | Allocates RAM to programs and keeps their active data organized. | Giving a browser memory for open tabs. |
| Device management | Coordinates communication with hardware through drivers and system services. | Sending a print job to a printer. |
| File management | Organizes files and folders and controls how they are stored and accessed. | Saving a document into a chosen folder. |
| User interface / shell | Lets a person control the computer through windows, menus, or typed commands. | Opening an app or running `pwd` in Terminal. |
| Security and permissions | Controls access to accounts, files, and system resources. | Requiring permission before an app accesses protected data. |

---

## 3. Commands / tools used
[Add the commands and applications you personally used, and explain their purpose.]

## 4. My understanding
[Rewrite the notes above in your own words and include what you observed.]

## 5. Difficulties faced
[Record actual difficulties, or “No major difficulties.”]

## 6. How I resolved them
[Record actual resolutions, or “Not applicable.”]

## 7. Evidence / files
[Add files and privacy-safe evidence actually included.]

## 8. Commit details
[Add the actual commit message and confirm that it was pushed.]

### Privacy-safe local observations actually available

The shell environment reports macOS 27.0.1. `python3 --version` reported Python 3.14.7; `git --version` reported Git 2.55.0. A filesystem summary for `/` reported about 926.3 GiB total, 12.7 GiB used, and 751.5 GiB available. A process snapshot through `ps` was denied with “operation not permitted”; no process list is claimed here. The active account name was intentionally left out of this public draft.
