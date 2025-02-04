# xterm-config
Configuration for XTerm terminal emulator

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
> Add line at the beginning of the file.
