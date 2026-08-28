# dotfiles

Personal Linux development environment managed with [chezmoi](https://www.chezmoi.io/).

## Environment

Optimized for Ubuntu (WSL2 and native dual-boot) with a focus on computational workflows.

## Contents

* Bash configuration and aliases
* Git configuration
* Package definitions and automated installation
* fcitx5 configuration
* Cloudflare WARP configuration
* Chezmoi templates and bootstrap scripts

## Bootstrap

Install and apply the configuration:

```bash
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply https://github.com/ht2905/dotfiles.git
```
