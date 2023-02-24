# DotAsh

> :rocket: A lightweight dotfile bootstrapper!
*Forked from [CallMeEchoCodes/dossier](https://github.com/CallMeEchoCodes/dossier)*

## 🚩 Table of Contents

- [Why Use DotAsh?](#-why-use-DotAsh)
- [Contributing](#-contributing)
- [Used By](#-used-by)
- [License](#-license)


## 🤖 Why Use DotAsh?
DotAsh is a tool that symlinks your dotfiles to where they should be. Allowing you to setup a computer really fast! While other alternatives exist DotAsh aims to be simpler than other alternatives without dependencies.

## :wrench: Installing
Install with Git: 
```sh
git clone https://github.com/Oppaiweeb/dotash.git
cp ./dotash/dotash ~/.local/bin/
```
be sure that ~/.local/bin/ is in your PATH
## 🔧 Contributing
DotAsh is open source, so you can create a pull request (PR). Simply `git clone` and your ready to go!
### Setup

You just need to DotAsh init inside your dotfile folder and add entry with DotAsh add
```sh
user@dotfile:dotash init
user@dotfile:dotash add
    >What file should i track? nvim
    >Where should that file be symlinked? (eg ~/.config) ~/.config
    >Is this file the same name as it will be when copied or different?
    ------------------------------------------------------------------
        > same
        different
user@dotfile:dotash install
```

### Develop

Fork and simply make your changes and submit a PR
### Pull Request

Before uploading your PR, test all features one last time to check if there are any errors. If it has no errors, commit and push it!

## 🚀 Used By

[Kawaegle's Dotfiles](https://github.com/kawaegle/dotfile)


## 📜 License

This software is licensed under the [WTFPL](http://www.wtfpl.net/about/).

## Contributers
[CallMeEchoCodes](https://github.com/CallMeEchoCodes/): Made dossier which this program is a fork of
