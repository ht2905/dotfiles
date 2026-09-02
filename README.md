# dotfiles

Personal Linux system configuration managed with [chezmoi](https://www.chezmoi.io/).

Optimized primarily for Ubuntu native dual-boot, with WSL2 supported to a lesser extent, with a focus on reproducible configuration and computational workflows.

## What's Included

A growing collection of personal system and development configurations, including:

* Shell and CLI configuration
* Git and development tools
* Package installation and system setup
* Input methods and desktop configuration
* Network and system services
* Application configuration
* Chezmoi templates and bootstrap scripts

## Bootstrap

Install and apply the configuration with:

```bash
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply https://github.com/ht2905/dotfiles.git
```

This initializes chezmoi from this repository and applies the configuration to the current system.