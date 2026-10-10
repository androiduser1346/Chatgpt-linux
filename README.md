# ChatGPT Linux 🐧

A Debian-based Linux desktop environment for Android using Termux,
PRoot, XFCE, and TigerVNC.

## Features
- Debian Linux environment
- XFCE desktop
- VNC remote desktop
- Custom chatgpt-linux launcher

## Requirements
- Android
- Termux
- proot-distro
- VNC Viewer

## Commands
Run these commands in Termux:

    chatgpt-linux start
    chatgpt-linux stop
    chatgpt-linux shell
    chatgpt-linux status

## VNC connection
Use 127.0.0.1:5901 when the VNC server is
running on the same device.

## Important
This is a PRoot-based Linux userland, not a
separate Linux kernel or bootable ISO.

## Clone the project

Run in Termux:

    pkg install -y git
    git clone https://github.com/androiduser1346/ChatGPT-Linux.git
    cd ChatGPT-Linux
    chmod +x chatgpt-linux

## Important
Cloning downloads the project files only. It does not download or install the Debian root filesystem automatically.
