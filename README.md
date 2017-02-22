# Prot16 themes for Vim Airline

**The files included in this repository are meant to complement the [Prot16 themes for Vim](https://github.com/protesilaos/prot16-vim).**

## Installation

If you use [vundle](https://github.com/VundleVim/Vundle.vim):

```
" add to .vimrc
Plugin 'protesilaos/prot16-vim'
:PluginInstall
```

## Use

Example using the `alto_dark` theme.

In your `.vimrc` file add this:

```
let g:airline_theme='alto_dark'
```

Or for a temporary switch within Vim:

```
:AirlineTheme alto_dark
```

## About this repo

The Prot16 collection was initially developed for the Atom text editor. This repository contains preliminary/experimental ports for the Vim Airline plugin for Vim. Support is provided both for GUI and terminal versions. 

However, the latter requires the implementation of the corresponding palette. This can be done either manually or by using one of the existing ports, as defined in each theme's project page.

For more on that refer to the following:

- Prot16 project pages: https://protesilaos.com/schemes
- Prot16 main git repo: https://github.com/protesilaos/prot16

## Miscelleneous

The files included in this repository were generated by the [Prot16 Builder](https://github.com/protesilaos/prot16-builder). A simple bash script was used to automate the process.

## License

GNU General Public License v3.0

