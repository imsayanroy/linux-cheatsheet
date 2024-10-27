# Vim cheatsheet
![vim editor](https://raspberrytips.com/use-vim-on-raspberry-pi/)
## Table of Contents
[Introduction](#introduction), [Installation](#installation), [Insert-mode](#insert-mode), [Exiting](#exiting).
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
- entry in insert mode
```bash
i
```
- exiting insert mode
```bash
Esc
```
## Exiting
- close file
```bash
:q
```
- save file
```bash
:w
```
- save and quit
```bash
:wq
```
- quit without saving
```bash
:q!
```
