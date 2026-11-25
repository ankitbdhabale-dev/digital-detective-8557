# Mission 2 — Become comfortable with the Terminal

> AI-assisted notes. The file operations and software versions below were performed or recorded in this session.

## Commands

| Command | Purpose |
|---|---|
| pwd | Print the current folder. |
| ls; ls -la | List visible files; the detailed form includes hidden entries and permissions. |
| cd .. | Move to the parent folder. |
| mkdir name | Create a directory. |
| touch file | Create an empty file. |
| cp source destination | Copy a file. |
| mv source destination | Move or rename a file. |
| cat file | Display a text file. |
| ls -la piped to head -n 5 | Show only the first five lines of a detailed listing. |

## Actual file practice

Created terminal-practice/notes.txt, wrote “first line”, appended “second line”, copied it to backup.txt, listed both files, and read notes.txt. The displayed contents were the two lines above. The owner permission bits were rw- (read/write, not executable).

## Package managers

A package manager finds, installs, updates, and removes software and dependencies. Homebrew version 7.0.15 was present. No packages were installed or removed; brew list --formula showed installed formulae.

## AI-assisted explanation

Appending preserves earlier text and adds new text at the end. Copying creates another file; moving or renaming changes where the same file is located. pwd and ls help check the location and files before editing. A pipe passes output from one command into another.

## Commit and evidence

The folder and practice files are public in mission-02-terminal. Original commit: “Complete Terminal and file management mission.” No usernames or full file paths are included.
