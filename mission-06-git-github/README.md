# Mission 6 — Git and GitHub

> Draft based on the assignment. Replace observation and reflection prompts with your own verified work and rewrite explanations in your own words before submission. Do not claim GitHub actions until they are actually visible.

## 1. Task / objective
Complete the tasks listed in this mission of the Digital Detective assignment.

## 2. Work completed and answer notes

## 6.1 Git workflow glossary

| Operation | What it does |
|---|---|
| Check repository status (`git status`) | Shows changed, staged, and untracked files. |
| Stage selected changes (`git add README.md`) | Selects changes to go into the next commit. |
| Create a commit (`git commit -m "Describe the work"`) | Saves a local snapshot of the staged changes with a message. |
| View commit history (`git log --oneline`) | Lists recent commits and their short descriptions. |

Staging chooses which edits belong together; committing records that chosen snapshot in local history. A commit is not automatically uploaded to GitHub.

## 6.2 Branch learning note — personalize

A branch is a separate line of project history where changes can be developed without immediately changing the main branch. I learned [YOUR TWO OR THREE REAL LEARNINGS FROM MISSIONS 0–5]. I created `update-about` and committed the README change with message [YOUR ACTUAL COMMIT MESSAGE]. Push status: [ACTUAL STATUS].

## 6.3 Branches and Pull Requests

A branch is a named line of development. A Pull Request (PR) proposes changes from one branch for review and discussion before they are merged into another. Branches and PRs let collaborators work separately, inspect differences, give feedback, and decide when changes should join the main project. **PR URL/status:** [CREATE AND RECORD YOUR ACTUAL PR; follow your instructor's merge instruction].

## 6.4 Git command glossary

- `git init` — start tracking a folder as a Git repository.
- `git status` — inspect staged, unstaged, and untracked changes.
- `git add <file>` — stage a chosen file's changes.
- `git commit -m "message"` — save staged changes in local history.
- `git log --oneline` — view a compact commit history.
- `git branch` — list branches; `git branch <name>` creates a branch.
- `git switch <name>` — move to another branch.
- `git push -u origin <name>` — publish a local branch to the remote and set its upstream.
- `git pull` — retrieve and integrate changes from the configured remote branch.

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

### Local Git status observed

`git init` initialized this local draft as a repository. `git status --short --branch` showed branch `master`, no commits yet, and the prepared mission files as untracked. There is no configured GitHub remote. No commit, branch publication, Pull Request, or push is claimed: the GitHub CLI token is invalid and the GitHub connection has not yet been confirmed.
