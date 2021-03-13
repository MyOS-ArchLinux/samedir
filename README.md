# samedir

This script lets you open a terminal window or a file manager
in the same directory as the currently active window.

### Requirements

- `xdotool` - get active window id
- `exo-open` - Xfce Preferred Applications framework frontend

## Installation

```
git clone https://github.com/MyOS-ArchLinux/samedir
cd samedir/
sudo install -m755 samedir /usr/local/bin/samedir
```
## Usage
```
samedir TerminalEmulator
samedir FileManager 
```
[set a keyboard shortcuts](https://wiki.archlinux.org/index.php/Keyboard_shortcuts)
