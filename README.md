# gnome-shell-extension-copyous

Arch Linux package for Copyous - a modern clipboard manager extension for GNOME Shell.

## Description

This repository contains the PKGBUILD and build configuration for packaging [Copyous](https://github.com/boerdereinar/copyous), a full rewrite of the Pano clipboard manager for GNOME Shell.

### Features

- Supports multiple content types: text, code, images, files, links, characters, and colors
- Pin favorite items and organize with 9 colored tags
- Customizable clipboard actions and highly configurable settings

## Building

To build the package locally:

```bash
cd pkgbuild
makepkg -si
```

## CI/CD

This package is automatically built and deployed via CI/CD pipeline.

## License

This packaging is under the MIT License - see the [LICENSE](LICENSE) file for details.

The Copyous extension itself is licensed under GPL-3.0-or-later.
