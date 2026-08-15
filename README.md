# ⚙️ Arch Linux Update & Clean Script

## 💡 About

This project is a simple and efficient automation script designed for Arch Linux users to update their system packages and clean up unnecessary cached files or orphaned dependencies in a single step.

## ✨ Features

* 🚀 **System Update:** Automatically updates all system packages using `pacman`.
* 📦 **Flatpak Support:** Updates and upgrades all installed Flatpak applications.
* 🧹 **Cache Cleanup:** Removes unnecessary cached files and packages to free up disk space.
* 🗑️ **Orphan Removal:** Uninstalls unused and orphaned Flatpak dependencies automatically.
* ⚡ **Fast & Automated:** Runs smoothly without requiring manual confirmation prompts (`--noconfirm`).

## 📋 Requirements

* 🐧 **Arch Linux:** A working Arch Linux (or Arch-based) distribution.
* 📦 **Pacman:** The standard Arch package manager (pre-installed by default).
* 🛍️ **Flatpak:** (Optional) Required if you want to update and clean Flatpak packages.
* 🔑 **Sudo Privileges:** Administrator rights to run package updates and system cleaning commands.

## 📥 Installation / Usage

1. **Download the script:**
   You can download the script directly to your system using this command:
   curl -O https://raw.githubusercontent.com/PoyrazAtalay/update-and-clean-arch-linux/main/update-clean.txt

2. **Run the script:**
   Whenever you want to update and clean your system, simply execute the following command in your terminal:
   bash update-clean.txt
