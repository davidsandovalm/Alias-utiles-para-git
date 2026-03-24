# Git Aliases Pro Setup

A curated collection of Git aliases designed to improve productivity, readability, and workflow efficiency when working in the terminal.

This configuration provides a faster, cleaner, and more intuitive Git experience for daily development.

---

## Overview

These aliases simplify common Git commands and introduce a powerful log visualization for better commit tracking.

They are globally configured and available across all repositories.

---

## Installation

Run the following commands in your terminal to register the aliases globally:

```bash
# Log visualization
git config --global alias.lg "log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"

# Status (short format)
git config --global alias.s status --short

# Status (branch + tracking)
git config --global alias.s "status -sb"

# Branch management
git config --global alias.b branch

# Commit with message
git config --global alias.co "commit -m"

# Add all changes
git config --global alias.a "add ."

# Checkout
git config --global alias.c checkout

# Merge
git config --global alias.m merge
