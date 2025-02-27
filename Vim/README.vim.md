# Vim cheatsheet
![vim editor](https://db0dce98.rocketcdn.me/en/files/2024/02/vim-editeur-text-datascientest-1024x512-1.png)
## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Insert mode](#insert-mode)
- [Exiting](#exiting)
## Introduction
Vim is a versatile text editor known for its speed and efficiency.

learn more: [`vim.org`](https://www.vim.org/)
## Installation
Here is the process to install Vim in Ubuntu/Kalilinux/Debian etc.
- update the package lists
```bash
sudo apt update
```
- upgrade the package lists
```bash
sudo apt upgrade
```
- install vim
```bash
sudo apt install vim
```
- check if installation is successful
```bash
vim --version
```
vim installation done!

## Insert mode
| **Commands** | **Description**         |
| :-------- | :------------------------- |
| `i` | enter insert mode |
| `Esc` | exit insert mode |
## Exiting
| **Commands** | **Description**         |
| :-------- | :------------------------- |
| `:q` | close file |
| `:w` | save file |
| `:wq` | save and close |
| `:q!` | close without saving |
