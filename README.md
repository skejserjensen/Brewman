# Brewman
Brewman is a thin wrapper around [homebrew](http://brew.sh/) and [homebrew cask](http://caskroom.io/) that simulates the command line interface of *pacman*, the package manager developed and used by Arch Linux. Brewman also implements functionality provided by *pacman* but lacking from *homebrew* or *homebrew cask*, such as removal of orphan dependencies when a formula is uninstalled and automatic update of casks.

Brewman requires both *homebew* and *homebrew cask* to be installed, and installs casks over formulas for simpler management due to their self contained nature. For those who uses *homebrew* exclusive and prefers a *pacman* style interface is the [pacapt](https://github.com/icy/pacapt) wrapper properly a better solution.

## Installation
1. Install *homebrew* and *homebrew cask*

2. Copy the script to a folder present in *$PATH*

3. Make the script executable using *chmod*

## License
The program is licensed under version 3 of the GPL, and a copy of the license is bundled with the program.
