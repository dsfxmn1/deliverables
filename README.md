# Agent Deliverables (GitHub Pages)

Public preview site for agent-produced HTML deliverables.

- Landing: https://dsfxmn1.github.io/deliverables/
- A page lives at `/<agent>/<slug>/index.html` → https://dsfxmn1.github.io/deliverables/<agent>/<slug>/

## Publishing
Agents with `exec` run:
```
publish-page <agent> <file.html> [slug]
```
which clones/pulls this repo, copies the file to `<agent>/<slug>/index.html`, commits, and pushes.
