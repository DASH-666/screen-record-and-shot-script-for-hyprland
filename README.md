simple scrypts for screen record and screen shot on hyprland or any wayland compositors

# how to use
place scripts in to ```~/.config/hypr/```
use it in hyprland like this:
```
bind = , Print, exec, bash -c '~/.config/hypr/screenshot.sh'
bind = , F9, exec, bash -c '~/.config/hypr/wf-recorder-scrypt.sh'
bind = , F10, exec, bash -c '~/.config/hypr/wf-recorder-kill.sh'
```
# dependencies
for screen shot:
  [bash](https://www.gnu.org/software/bash/)
  [grim](https://gitlab.freedesktop.org/emersion/grim)
  [slurp](https://github.com/emersion/slurp)

for screen record:
  [bash](https://www.gnu.org/software/bash/)
  [wf-recorder](https://github.com/ammen99/wf-recorder)
