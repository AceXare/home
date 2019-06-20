<div>
  <h1 align="center">Home</h1>
  <h3 align="center"><img src="data/icons/64/com.github.manexim.home.svg"/><br>Control your smart home gadgets</h3>
  <p align="center">Designed for <a href="https://elementary.io">elementary OS</a></p>
</div>

[![Build Status](https://img.shields.io/travis/manexim/home.svg)](https://travis-ci.org/manexim/home)
[![GitHub release](https://img.shields.io/github/release/manexim/home.svg)](https://github.com/manexim/home/releases/)
[![License](https://img.shields.io/github/license/manexim/home.svg)](https://github.com/manexim/home/blob/master/COPYING)

![screenshot](data/screenshots/000.png)
![screenshot](data/screenshots/001.png)
![screenshot](data/screenshots/002.png)
![screenshot](data/screenshots/003.png)
![screenshot](data/screenshots/004.png)

## Installation

### Dependencies
These dependencies must be present before building
 - `elementary-sdk`
 - `meson (>=0.40)`
 - `valac (>=0.40)`
 - `libgtk-3-dev`
 - `libjson-glib-dev`
 - `libgee-0.8-dev`
 - `libgranite-dev`
 - `libsoup2.4-dev`
 - `libxml2-dev`
 - `uuid-dev`

### Building

```
git clone https://github.com/manexim/home.git && cd home
meson build && cd build
meson configure -Dprefix=/usr
ninja
sudo ninja install
com.github.manexim.home
```

### Deconstruct

```
sudo ninja uninstall
```
