# Fedora + Hyprland

My personal Fedora Linux workstation built around Hyprland.

The goal is a simple, fast and keyboard-driven desktop that stays comfortable
during long coding sessions without turning into a heavily customized "rice".

![Desktop](screenshots/desktop.png)

## System

- Fedora Linux 44 Workstation
- Hyprland 0.56.2
- Wayland
- ASUS Zenbook 14 UX3405CA
- Intel Core Ultra 5 225H
- Intel Arc graphics
- 16 GB RAM
- 1 TB NVMe SSD
- 2880×1800 @ 120 Hz display

## Setup

| Tool | Purpose |
|------|---------|
| Hyprland | Tiling window manager |
| Kitty | Terminal |
| Waybar | Status bar |
| Rofi | Application launcher |
| Dolphin | File manager |
| Dunst | Notifications |
| Zsh + Starship | Shell and prompt |
| Firefox | Web browser |

## Hyprland

My Hyprland setup focuses on a clean tiling workflow:

- 4px inner gaps
- 8px outer gaps
- 8px rounded corners
- Smart gaps for single-window workspaces
- Tokyo Night-inspired colors
- Application-based workspace rules
- Keyboard-first workflow

## Terminal

Kitty with:

- JetBrains Mono Nerd Font
- Font size 11
- Tokyo Night
- Custom padding and scrollback
- Copy-on-select

![Terminal](screenshots/terminal.png)

## Workflow

The setup is designed around keyboard-driven navigation and development.

- Rofi for launching applications
- `cliphist` for clipboard history
- Hyprland workspaces for separating different tasks
- Kitty for Git, C++, Python and system work
- Firefox for documentation, Codeforces, CSES and research

## Design Philosophy

I wanted the desktop to be:

- Minimal
- Fast
- Dark and OLED-friendly
- Comfortable for long coding sessions
- Easy to maintain

I deliberately avoided heavy transparency, animated wallpapers and
unnecessary visual effects.

## Repository

This repository contains the configuration files I use for my Fedora +
Hyprland setup.

It is mainly intended as a record of my workstation and as a way to keep
my configuration backed up and reproducible.