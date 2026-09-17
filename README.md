# ARX Browser

A lightweight Linux browser built from scratch in C++ using GTK3 and WebKitGTK.

ARX Browser is focused on keeping the browser simple, fast, and under direct control of the project rather than trying to be another full-scale Chromium or Firefox clone.

## Current Release

**v0.3.0 — Linux x86_64**

[Download ARX Browser](https://github.com/lulitaxu/ARXBrowser-Releases/releases/latest)

## Features

- Web browsing with WebKitGTK 4.1
- Multiple tabs
- Address bar
- Back / Forward navigation
- Reload
- New tab
- ARX home page
- Basic privacy controls
- Lightweight custom interface

## Requirements

Currently built and tested on Linux x86_64.

The binary requires:

- GTK3
- WebKitGTK 4.1

### Arch Linux

```bash
sudo pacman -S gtk3 webkit2gtk-4.1
```
```Installation
```

Download the latest release:

ARX Browser Releases

Then extract the archive:
```bash
tar -xzf ARX-Browser-v0.3.0-Linux-x86_64.tar.gz
```
Enter the extracted directory:
```bash
cd ARX-Browser
```
Run:
```bash
./arx-browser
```
Project

ARX Browser is written in C++.

The current browser UI is built with:

GTK3
WebKitGTK 4.1
CMake
C++20
Status

ARX Browser is still an early-stage project.

The current release is mainly focused on the browser interface, tabs, navigation controls, and getting the core browser architecture in place.

More browser functionality will be added as development continues.

