# Lesson 00 Laboratory Commands

## Purpose

This document records important commands used during the initial laboratory setup.

The purpose is not memorizing commands, but understanding their role in the engineering workflow.

---

# Repository Inspection

Check repository status:

```bash
git status
```

Purpose:

Verify the current branch, synchronization state, and pending changes.

---

Display repository files:

```bash
ls -la
```

Purpose:

Inspect the project structure.

---

Display directory hierarchy:

```bash
find . -maxdepth 2 -type d | sort
```

Purpose:

Review repository organization.

---

# Git Workflow

Review changes:

```bash
git status
```

Stage files:

```bash
git add .
```

Create a commit:

```bash
git commit -m "Commit message"
```

Synchronize with GitHub:

```bash
git push
```

---

# Verification

Check commit history:

```bash
git log --oneline --graph
```

Purpose:

Understand project evolution through Git history.

---

# Notes

Commands are recorded together with their purpose because understanding the reason behind a command is more important than memorizing syntax.

