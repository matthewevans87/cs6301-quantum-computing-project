# UT Dallas - CS 6301 (Quantum Computing) Semester Project

This repository contains an article and presentation responding to _Ramesh & Vinay (2003)_.

## Tips

- Adhere to the `.gitignore` file's rules; this means no image files, extra notes, etc.
- Use [VS Code](https://code.visualstudio.com/).
- Use the Source Control feature inside of VS Code to manage commits.
- Use the GitHub [CLI tool](https://cli.github.com/).
- Use AI tools to handle boilerplate work such as generating the LaTeX code for a problem's text.
- Use the following VS Code extensions, all of which are included in this project's [workspace recommended extensions](https://code.visualstudio.com/docs/editor/extension-marketplace#_workspace-recommended-extensions).
  - [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
  - [GitHub Copilot Chat](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-chat)
  - [LaTeX Workshop VS Code Extension](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
  - [GitHub Pull Requests](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)
- GitHub Copilot is particularly helpful for resolving LaTex errors and generating things like tables, graphs, expressions, mathematical symbols, adjusting formatting, etc.

## Quick Git Guide

_Git_ is a source control and change tracking system. You install it locally on your computer. A Git _repository_ is a directory in which changes are being tracked by Git. Changes are "saved" to the repository in the form of _commits_. Files must be _added_ to the repository before they are _tracked_ by Git. Git commits can be thought of as topologically ordered set of edits. These "graphs" of changes can be merged.

GitHub is a website/service where Git repositories can be remotely hosted. Your local copy of the repository (i.e., your graph of changes) can be _merged_ with this remote copy, enabling everyone else to _pull_ your changes.

All of your work should be within a new **branch**, branched off of `main`.

Example:

```
git checkout main
git pull
git checkout -b short-description-of-work
```

When you are read to submit your work, you need to **commit** your work.

Example:

```
git add .
git commit -m 'update paragraph explaining superposition'
```

When new changes are available, they must be _pulled_ down to your local copy.

```
git checkout main
git pull
```

If new changes have been added to `main` (or some other branch) and you need those changes locally...

```
git checkout main
git pull
git checkout <yourbranch>
git merge main
```

## Further Reading

If you want to become a git guru, check out [Learn Git Branching](https://learngitbranching.js.org/?locale=en_US)!
