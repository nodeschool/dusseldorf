---
layout: main
title: Setup Guide
---

## On Windows

- Download the [Node.js Installer][nodejs-website].
- Make sure to select the current (>7) version.

## On MacOS

### Using [Homebrew][homebrew]

- Just type `brew install nodejs` into your terminal.

### Manually

- Download the latest `.pkg` from http://nodejs.org and install it.

## On Linux/UNIX

### Using [nvm]

- Install `nvm` from https://github.com/creationix/nvm
- Execute `nvm install node` in a terminal.
- Set the installed version as default by executing `nvm alias default node`.

### Using other package managers

[This page][nodejs-package-managers] has information for most big UNIX package
managers out there.

## Did it work?

Type `node --version` and `npm --version` into your terminal of choice. If you
get an error, ask the mentors for help!

[nodejs-website]: http://nodejs.org/
[homebrew]: http://brew.sh/
[nvm]: https://github.com/creationix/nvm
[nodejs-package-managers]: https://nodejs.org/en/download/package-manager/
