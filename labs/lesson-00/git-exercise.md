# Lesson 00 Lab - Git Exercise

## Objective

Practice the basic Git workflow used throughout the Operating Systems Laboratory project.

---

# Workflow

The laboratory follows this sequence:

```text
Modify files
     |
     v
Review changes
     |
     v
Stage files
     |
     v
Create commit
     |
     v
Push to GitHub
```

---

# Basic Commands

## Check repository status

```bash
git status
```

Purpose:

Understand the current state of the working tree.

---

## Review changes

```bash
git diff
```

Purpose:

Inspect modifications before committing.

---

## Stage changes

```bash
git add .
```

Purpose:

Prepare selected changes for commit.

---

## Commit changes

```bash
git commit -m "Describe the change"
```

Purpose:

Create a permanent point in project history.

---

## Synchronize repository

```bash
git push
```

Purpose:

Publish local history to GitHub.

---

# Engineering Rule

A commit should represent a meaningful change.

Examples:

Good:

```text
Add Lesson 0 environment documentation
```

Bad:

```text
update files
```

---

# Result

The repository now provides a traceable history of development activities.

