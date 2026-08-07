# Lesson 00 - Engineering Decisions

## Purpose

This document records important architectural and workflow decisions made during the creation of the Operating Systems Laboratory repository.

The goal is to preserve the reasoning behind choices, not only the final result.

---

# Repository Structure Decision

## Decision

The repository is organized into separate areas:

```
docs/
labs/
src/
scripts/
references/
```

## Reason

Operating system development requires understanding both theory and implementation.

Separating documentation from experiments and source code allows:

* concepts to be explained clearly,
* experiments to remain reproducible,
* implementation to evolve independently.

---

# Documentation-First Decision

## Decision

Documentation is created together with development activities.

## Reason

Operating systems are complex systems involving many layers:

* hardware,
* architecture,
* kernel,
* drivers,
* networking,
* user applications.

Without documentation, understanding becomes difficult as complexity increases.

---

# Git History Decision

## Decision

Git commits should represent meaningful engineering steps.

## Reason

The repository history should show the development journey.

A future reader should understand:

* when a feature was introduced,
* why a decision was made,
* how problems were solved.

---

# Learning Approach Decision

## Decision

The laboratory follows a gradual path from fundamentals to implementation.

## Reason

Operating systems require knowledge from multiple domains:

* computer architecture,
* programming languages,
* assembly,
* memory,
* processes,
* networking.

Building foundations first reduces complexity in later implementation stages.

---

# Future Expansion

This decision record will continue evolving as new lessons introduce:

* bootloader experiments,
* kernel components,
* hardware interaction,
* network systems,
* embedded platforms.

