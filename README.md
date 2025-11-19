# Dotfile-Omarchy
My personal linux configuration for building off of Omarchy.

Managed with **chezmoi** and bootstrapped using **Ansible**.

The goal is a to apply the principles of **Infrastructure As Code** to my dotfiles.

## Overview

* **chezmoi** handles all dotfiles, templates, and host-specific configs.

* **Ansible** applies system-level setup such as packages, services, and machine configuration.

* **Emacs** is the primary editing environment (Elpaca-based, modular config), but for now is [managed separately](https://github.com/ewhd/emacs).

## Design Principles

* **Infrastructure As Code**:

* **Prefer Low Abstraction Over High**:



## Requirements

* Omarchy

* Git

* chezmoi

* Python 3 (for Ansible)

* ~~Ansible ≥ 2.14~~ --> installed by chezmoi during setup


## Overview

chezmoi handles all dotfiles, templates, and host-specific configs.

Ansible applies system-level setup such as packages, services, and machine configuration.

Emacs is the primary editing environment (Elpaca-based, modular config).

## Requirements

Git

chezmoi

Python 3 (for Ansible)

Ansible ≥ 2.14
