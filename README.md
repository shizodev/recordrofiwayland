# Wayland fork (Tested on Hyprland)
Dependencies: wf-recorder, rofi, ffmpeg, slurp, jq

# Rofi recording script
Record your screen, desktop audio and microphone input at the same time

## Changing microphone
If the default microphone source doesn't work for you, then execute the following command:
```
pactl list sources short
```
Find your microphone there and change `$mic_source` variable in the `recordrofi` script.

## Installation
```
$ git clone https://github.com/shizodev/recordrofiwayland
$ cd recordrofi
$ chmod +x ./install-theme.sh recordrofi
$ ./install-theme.sh
$ sudo mv recordrofi /usr/bin
```
Have fun!
```
$ recordrofi
```


