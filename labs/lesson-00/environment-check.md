# Lesson 00 Lab - Environment Check

## Objective

Verify that the development environment is ready for the Operating Systems Laboratory project.

The purpose of this step is to establish a known baseline before starting deeper system experiments.

---

# System Information

The laboratory environment is based on:

* Linux operating system
* Ubuntu 24.04 LTS
* Virtual machine development environment
* Bash shell

---

# Verification Commands

## Check operating system information

```bash
uname -a
```

Purpose:

Verify kernel and system information.

---

## Check distribution information

```bash
cat /etc/os-release
```

Purpose:

Identify Linux distribution and version.

---

## Check current user

```bash
whoami
```

Purpose:

Verify the active development account.

---

## Check available tools

```bash
git --version
gcc --version
make --version
```

Purpose:

Confirm required development tools are installed.

---

# Expected Result

The environment should provide:

* Linux command-line access.
* Git version control.
* Compiler toolchain.
* Build automation tools.

---

# Conclusion

The environment check creates a reproducible starting point for future operating system experiments.

