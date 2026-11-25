# Mission 2 — Become comfortable with the Terminal

> Draft based on the assignment. Replace observation and reflection prompts with your own verified work and rewrite explanations in your own words before submission. Do not claim GitHub actions until they are actually visible.

## 1. Task / objective
Complete the tasks listed in this mission of the Digital Detective assignment.

## 2. Work completed and answer notes

## 2.1 Command reference

| Operation | macOS / Linux command | Purpose / observation |
|---|---|---|
| Current directory | `pwd` | Prints the full path of the current folder. Record your safe project-folder path: [YOUR OBSERVATION] |
| List files | `ls` | Lists visible entries in the current folder. |
| Detailed listing | `ls -la` | Shows hidden entries and details such as permissions, owner, size, and modification time. |
| Go to parent | `cd ..` | Moves up one folder; `pwd` then shows the changed location. |
| Create directory | `mkdir terminal-practice` | Creates a folder named `terminal-practice`. |
| Create empty file | `touch notes.txt` | Creates an empty file (or updates its timestamp if it exists). |
| Copy file | `cp notes.txt notes-copy.txt` | Makes a second file while leaving the original in place. |
| Rename / move | `mv notes-copy.txt backup.txt` | Changes the name, or moves the file if the destination is another folder. |
| Display contents | `cat notes.txt` | Prints a text file's contents in the terminal. |

## 2.2 Safe file changes

Replacing a file's contents removes the old contents and writes new ones; appending adds text after the existing contents. Copying creates another file while keeping the original; moving relocates or renames the same file. `pwd` helps confirm where a command will act. A directory listing is useful for checking names and whether the expected files exist.

## 2.3 Flags and pipes

A flag changes a command's options. `ls` shows a basic list; `ls -la` also includes hidden entries and detailed metadata. A pipe (`|`) sends one command's output to another command as input. For example, `ls -la | head -n 5` displays only the first five lines of the listing. The left command produces the list; `head` selects its first lines.

## 2.4 Package managers

A package manager keeps a catalogue of software and automates finding, installing, updating, and removing packages and their dependencies. This makes software versions and maintenance more consistent than locating every component manually. **If Homebrew is installed:** [record `brew --version` and `brew list` results without installing or uninstalling anything]. If it is not installed, package managers such as Homebrew can still be described without installing one for this assignment.

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

### Safe practice actually performed

Inside this repository, I created `terminal-practice/notes.txt`, wrote one line, appended a second line, copied the file, renamed the copy to `backup.txt`, listed the practice folder, and displayed the original. The displayed contents were `first line` and `second line`; both files were present. The detailed listing showed file sizes and permissions; account-identifying owner/path fields were omitted from this report.

Homebrew is installed; `brew --version` reported 7.0.15. `brew list --formula` showed installed formulae. No packages were installed or removed for this mission. The practice file's owner permission bits were `rw-` (read/write, not executable); its full listing owner field is omitted for privacy. Moving from the project root into `mission-02-terminal` changed the relative current directory as expected.
