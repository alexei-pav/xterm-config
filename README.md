# xterm-config
Configuration for XTerm terminal emulator

## Requirements
 - CommitMono Nerd Font (but you can change it in Xresourses file)
 - XTerm Terminal Emulator

## Installation 
First, type this:
```shell
mkdir -p $HOME/.config/xterm && git clone https://github.com/alexei-pav/xterm-config.git $HOME/.config/xterm
```
Then, add this to your .xinitrc file:
```shell 
xrdb -load $HOME/.config/xterm/Xresources
```
> [!IMPORTANT]
> If the file has content, then add it to the beginning.
