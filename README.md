simple scrypts for screen record and screen shot on hyprland or any wayland compositors
place scripts in to ```~/.config/hypr/```
use it in hyprland like this:
```
bind = , Print, exec, bash -c '~/.config/hypr/screenshot.sh'
bind = , F9, exec, bash -c '~/.config/hypr/wf-recorder-scrypt.sh'
bind = , F10, exec, bash -c '~/.config/hypr/wf-recorder-kill.sh'
```
