# pkg publish

This action publishes all installation scripts and packages to the `gh-pages` branch.

## Install Scripts
All scripts in the `install` directory are just copied to the root of the `gh-pages` branch.

## Arch Packages
This action builds a package for Arch Linux with [makepkg](https://wiki.archlinux.org/index.php/Makepkg).
