---
name: stage-new-files
description: Stage new files created while working in this repository. Apply whenever a task creates files, including documentation, configuration, and skills.
---

Whenever you create a new file for the current task, add it to Git with `git add -- <path>` before finishing the task. Respect `.gitignore`; do not force-add ignored files unless the user explicitly requests it.

Stage only files created for the current task. Leave unrelated untracked files and existing user changes alone. Use explicit paths instead of `git add .` or `git add -A`.

Before finishing, check `git status --short` and confirm that every new, non-ignored task file is staged. Staging does not authorize a commit or push.
