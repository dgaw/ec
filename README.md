# ec - An Emacs startup script for modern desktops

A wrapper script for *emacsclient* that opens a file in existing Emacs 
or launches a new instance if Emacs is not running.

It's useful if you want to have one instance of Emacs running and be
able to open files in it using the terminal or "Open with" actions in 
your file manager.

## Features
* Works with terminal-only and GUI-based Emacs
* Focuses the Emacs window (requires xdotool)
* Non-blocking

## Requirements
* Linux (may or may not work on MacOS X - let me know)
* [xdotool](https://www.semicomplete.com/projects/xdotool/) (optional - for focusing the Emacs window)

## Installation

```
cd ~/.local/bin
wget https://raw.githubusercontent.com/dgaw/ec/master/bin/ec
chmod +x ec
```

## Usage
```
ec FILENAME
```
