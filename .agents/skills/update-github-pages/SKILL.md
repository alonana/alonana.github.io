---
name: update-github-pages
description: Publish and verify updates to this repository's GitHub Pages site using SSH.
---

- Site: My Biology Journey — https://alonana.github.io/
- Remote: `git@github.com:alonana/alonana.github.io.git`; branch: `main`.
- Jekyll with Minima; GitHub Pages builds from the repository root.

Use `git -c core.sshCommand="ssh -i $HOME/.ssh/github -o IdentitiesOnly=yes"` for GitHub operations.
When publishing is requested, commit the task's changes and push to `origin main`. Wait for the Pages deployment and verify the change on the live site.
