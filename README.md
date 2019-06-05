# DMH (Dual Monitor Helper)
![](./preview.png)

## Introduction
On some Linux distribution, newly connected monitor may not detect resolution profile correctly, (i.e. It only recognizes low resolution profiles like 1024x768). This application aims at solving this problem. When you plug your display to the interface, you can use DMH to add new resolution profiles. All profiles created by DMH is temperory added and this program will not apply the monitor setting automatically.

## Support Platform
- [x] Linux

## Dependency
- Xrandr

## Installation
```bash
# Download Xrandr on Linux
sudo pacman -S xorg-xrandr

# Download repo
git clone git@github.com:awaSwasA/dmh.git

# Install require packages
cd dmh
npm install --save-dev

# Generate Binary
electron-packager .

# Execute the application
./dual-monitor-helper-linux-x64/dual-monitor-helper
```
