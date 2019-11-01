# MagiskEmi

_This was originally a fork of TerminalModifications but ended up being a frankenstein of several projects._

## Description
This module systemlessly adds some binaries by default, particularly the bash prompt.
Other included binaries are eventrec (a event recorder and player), and strace (er..).

~~Unfortunately `adb shell` does not spawns the bash binary automatically, you have to type it in (WIP).~~


## Instructions
- Install the module from the Magisk Manager's Downloads section, then reboot.
- Go to /sdcard and edit .bashrc if you want to change things.

## Changelog

### 4.0
- Suddenly, things work. `bash` runs automatically when opening an `adb shell` without the need to recompile `adbd`.
- Also, following new practices and unity versions.

### 3.6
- Can't even make a changelog.

### 2.1
- Bash completion
- Auto installs busybox utilities
- Better aliases

### v1.1
- Trying to make `bash` open by default when running `adb shell` without having to recompile `adbd`.

### v1.0
- Project forked by @esauvisky
- New PS1, PS2 and PS3.
- Different aliases.
- A custom built `bash` binary.
- Other binaries bundled in, like `eventrec` and `strace`.