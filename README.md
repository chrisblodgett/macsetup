# 🍎 Mac Setup Guide

Welcome to **macsetup.md** — a personal reference for restoring and configuring my preferred macOS development environment. This guide covers the tools, configurations, and settings I use to make a Mac ready for productive work, from terminal customization to essential apps and development utilities.

> Use this to quickly bootstrap a fresh Mac or reconfigure an existing one to match my ideal workflow.
---

## 🍺 Install Homebrew and XCode command line tools.

[Homebrew](https://brew.sh/) is the macOS package manager I use to install and manage software from the command line. It simplifies the setup of essential tools and applications. Below will also install Xcode command line Tools.

### 🔧 Installation

Run the following command in Terminal:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
---

## 🧭 Install Microsoft Edge Browser

Microsoft Edge is my preferred browser for its performance, privacy features, and Chromium-based developer tools.

### 🔧 Installation (via Homebrew)

```bash
brew install --cask microsoft-edge
```
---

## 🐱 Install Kitty Terminal

[Kitty](https://sw.kovidgoyal.net/kitty/) is a fast, GPU-accelerated terminal emulator that supports ligatures, tabs, and modern features out of the box. It's my preferred terminal for development work.

### 🔧 Installation (via Homebrew)

```bash
brew install --cask kitty
```
---

## 🐚 Set Up Zsh and Oh My Zsh

Zsh is the default shell on macOS, but this section ensures it's set and enhanced with [Oh My Zsh](https://ohmyz.sh/) — a framework for managing Zsh configuration with themes, plugins, and sensible defaults.

### 🔧 Ensure Zsh is Installed

macOS ships with Zsh preinstalled. To verify:

```bash
zsh --version
```
if not change it with
```bash
chsh -s /bin/zsh
```
## 💫 Install Oh My Zsh

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```


