# Lesson 0 – Operating System Foundations

## Objectives

The purpose of this lesson is to build a solid conceptual foundation before studying individual operating system components. Instead of immediately focusing on processes, memory management, or scheduling, this lesson explains how an operating system fits into the complete computer system.

## Learning Outcomes

After completing this lesson, I can:

* Explain why operating systems exist.
* Describe the relationship between hardware, firmware, the bootloader, the kernel, user space, libraries, and applications.
* Explain the difference between user mode and kernel mode.
* Describe the purpose of system calls.
* Explain the Linux boot sequence at a high level.
* Analyze a running Linux system using standard command-line tools.
* Think about operating systems from an engineering and design perspective rather than only from an implementation perspective.

## Laboratory Environment

| Item             | Value                  |
| ---------------- | ---------------------- |
| Operating System | Ubuntu 24.04.4 LTS     |
| Kernel           | Linux 7.0.0-28-generic |
| Architecture     | x86-64                 |
| CPU              | Intel® Core™ i5-5200U  |
| Memory           | 4 GB RAM               |
| Environment      | Ubuntu Virtual Machine |

## Topics Covered

* What is an operating system?
* Why operating systems exist.
* Hardware and software responsibilities.
* Firmware and the boot process.
* Bootloader responsibilities.
* Kernel initialization.
* User space and kernel space.
* CPU privilege levels.
* System calls.
* Process hierarchy.
* The role of PID 1 (`systemd`).
* Engineering thinking for operating system design.

## Linux Investigation

During this lesson, the following Linux tools and interfaces were used:

* `uname`
* `lscpu`
* `lsblk`
* `free`
* `mount`
* `/proc`
* `/boot`
* `findmnt`
* `ps`
* `strace`

These tools were used to verify theoretical concepts by observing a real Linux system.

## Key Experiments

* Investigated the Linux boot configuration.
* Examined kernel boot parameters.
* Identified the first user-space process (`systemd`).
* Observed system calls using `strace`.
* Explored the relationship between user applications and the kernel.
* Investigated the organization of the Linux filesystem during boot.

## Engineering Observations

A modern operating system is not simply a collection of features. It is an architecture that divides responsibilities among hardware, firmware, the kernel, libraries, and user applications. Understanding these responsibilities is essential before studying individual operating system mechanisms.

Rather than memorizing Linux-specific details, this lesson focused on understanding the design principles that are common to many operating systems.

## Key Takeaways

Lesson 0 established the architectural framework that will be used throughout the Operating Systems Laboratory. Future chapters will build on this foundation by connecting each new concept to Linux implementation, operating system design decisions, and practical experiments.

## Next Lesson

**Chapter 1 – Processes**

