# Google Cursor

An OpenSource cursor theme inspired by Google.

[![Build](https://github.com/ful1e5/Google_Cursor/workflows/build/badge.svg)](https://github.com/ful1e5/Google_Cursor/actions?query=workflow%3Abuild)
[![CodeFactor](https://www.codefactor.io/repository/github/ful1e5/google_cursor/badge)](https://www.codefactor.io/repository/github/ful1e5/google_cursor)
[![Twitter](https://img.shields.io/badge/twitter-ful1e5-blue)](https://twitter.com/ful1e5)

#### Cursor Sizes

<kbd>22</kbd>
<kbd>24</kbd>
<kbd>28</kbd>
<kbd>32</kbd>
<kbd>40</kbd>
<kbd>48</kbd>
<kbd>56</kbd>
<kbd>64</kbd>
<kbd>72</kbd>
<kbd>80</kbd>
<kbd>88</kbd>
<kbd>96</kbd>

#### Colors

![#4285F4](https://imgur.com/NXEup6E.png)
![#FFFFFF](https://imgur.com/cvFxSBb.png)

### Quick install

<p align="center">
  <a href="https://www.pling.com/p/1215613/" >
    <img title="GoogleDot Pling Store" width="40%" src="https://imgur.com/VxSgrWw.png">
  </a>
</p>

#### Install with package manager

##### ArchLinux/Manjaro (AUR)

```bash
yay -S googledot-cursor-theme
```

### Preview:

> Check Figma file [here](https://www.figma.com/file/i7nfGDWCTWlNJlnhmvHDfh/Google-Cursor?node-id=0%3A1)

<!-- Preview -->

<p align="center">
  <img title="GoogleDot Blue" src="https://imgur.com/osnWiED.png">
</p>

<p align="center">
  <img title="GoogleDot Black" src="https://i.imgur.com/9ZlC1gD.png">
</p>

<p align="center">
  <img title="GoogleDot White" src="https://i.imgur.com/67KgJ3s.png">
  </br>
</p>

<p align="center">
  <img title="GoogleDot Red" src="https://imgur.com/VtauWGC.png">
  </br>
</p>

### Manual Install

#### Linux/X11

```bash
# extract `GoogleDot.tar.gz`
tar -xvf GoogleDot.tar.gz

# For local users
mv GoogleDot-* ~/.icons/

# For all users
sudo mv GoogleDot-* /usr/share/icons/
```

#### Windows

1. unzip `.zip` file
2. Open unziped directory in Explorer, and **right click** on `install.inf`.
3. Click 'Install' from the context menu, and authorize the modifications to your system.
4. Open _Control Panel > Personalization and Appearance > Change mouse pointers_, and select **GoogleDot Cursors**.
5. Click '**Apply**'.

<!-- Build Dependencies -->

# Dependencies

## External Libraries

- libxcursor
- libx11
- libpng (<=1.6)

#### Install External Libraries

##### macOS

```bash
brew install --cask xquartz
brew install libpng
```

##### Debain/ubuntu

```bash
sudo apt install libx11-dev libxcursor-dev libpng-dev
```

##### ArchLinux/Manjaro

```bash
sudo pacman -S libx11 libxcursor libpng
```

##### Fedora/Fedora Silverblue/CentOS/RHEL

```bash
sudo dnf install libX11-devel libXcursor-devel libpng-devel
```

## Build Dependencies

- [gcc](https://gcc.gnu.org/install/)
- [make](https://www.gnu.org/software/make/)
- [nodejs](https://nodejs.org/en/) (<=12.x.x)
- [yarn](https://classic.yarnpkg.com/en/docs/install/)
- [python](https://www.python.org/downloads/) (<=3.8)
- [pip3](https://pip.pypa.io/en/stable/installing/)

### Node Packages

- [puppeteer](https://www.npmjs.com/package/puppeteer)
- [pngjs](https://www.npmjs.com/package/pngjs)
- [pixelmatch](https://www.npmjs.com/package/pixelmatch)

### PyPi Packages

- [clickgen](https://pypi.org/project/clickgen/s)

## Build Dependencies

- [gcc](https://gcc.gnu.org/install/)
- [make](https://www.gnu.org/software/make/)
- [nodejs](https://nodejs.org/en/) (<=12.x.x)
- [yarn](https://classic.yarnpkg.com/en/docs/install/)
- [python](https://www.python.org/downloads/) (<=3.8)
- [pip3](https://pip.pypa.io/en/stable/installing/)

### Node Packages

- [puppeteer](https://www.npmjs.com/package/puppeteer)
- [pngjs](https://www.npmjs.com/package/pngjs)
- [pixelmatch](https://www.npmjs.com/package/pixelmatch)

### PyPi Packages

- [clickgen](https://pypi.org/project/clickgen/s)

## Build From Scratch

### ⚡ Auto Build (using GitHub Actions)

GitHub Actions is automatically runs on every `push`(on **main** and **dev** branches) and `pull request`(on **main** branch), You found theme resources in `artifact` section of **build**.GitHub **Actions** available inside [.github/workflows](https://github.com/ful1e5/Google_Cursor/tree/main/.github/workflows) directory.

### Manual Build

```bash
make
```

#### Build `XCursor` theme

```bash
make unix
```

#### Customize `XCursor` size

```bash
make unix X_SIZES=22            # Only built '22px' pixel-size.
make unix X_SIZES=22 24 32      # Multiple sizes are provided with  ' '(Space)
```

#### Install `XCursor` theme

```bash
make install            # install as user
  # OR
sudo make install       # install as root
```

#### Build `Windows` theme

```bash
make windows
```

#### Customize `Windows Cursor` size

```bash
make windows WIN_SIZE=96            # Supports only one pixel-size
```

> For installation follow [these](#windows) steps.

<!-- Bug Report -->

# Bugs

Bugs should be reported [here](https://github.com/ful1e5/Google_Cursor/issues) on the Github issues page.

<!-- Help -->

# Getting Help

You can create a **issue**, I will help you. 🙂

<!-- Contributions and Suggestion -->

# Contributing

Check [CONTRIBUTING.md](CONTRIBUTING.md), any suggestions for features and contributions to the continuing code masterelopment can be made via the issue tracker or code contributions via a `Fork` & `Pull requests`.

<!-- Support -->

## Support

<a href="https://www.buymeacoffee.com/Nt7Wg4V" target="_blank">
  <img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" >
</a>

<!-- Ninja  -->

<h1 align="center">
  ( `ω´ )۶▬ι═══════ﺤ
</h1>
<p align="center">
  <sub>I'm Using Katana </sub>
</p>
