# dotconfig(1)

A set of application configurations I tend to use when setting up a new computer.

It's becoming a fairly common practice for applications to store their configuration in the `$HOME/.config` directory; this is an automated process for setting up the directory and storing non-personal information.

**N.B.** This project has a [Code of Conduct](./.github/CODE_OF_CONDUCT.md). By interacting with this repository, organization, and/or community you agree to abide by its terms.

## Installation

:warning: This will overwrite your existing `.dotconfig` directory.

```bash
$ /bin/bash -c "$(curl -#fL https://raw.githubusercontent.com/iamnewton/dotconfig/main/bin/dotconfig)"
```

### Requirements

Ensure that you have the following dependencies installed on your system.  If you're on MacOS then you already have these, but a Linux system may not come with all.

* [curl](http://curl.haxx.se)
* [git](http://git-scm.com)

## Features

* [Github CLI](https://cli.github.com/)
* `nvim` via [LazyVim](https://www.lazyvim.org/)

* * *

## Acknowledgements

Inspiration and code was taken from the following sources (in lexicographical order):

* [My Entire Neovim + Tmux Workflow As A DevOps Engineer On MacOS](https://www.youtube.com/watch?v=iagjeLuxnMs)
