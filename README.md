# udev-rules
Here I Store some udev rules I use in my system.

## 99-screens.rules
### Requires
- xpub
- autorandr
- dunst
### What it Does
Detect plug/unplug of HDMI Cable, and use `autorandr --change` command to load a screen profile.
Then use `dunstify` command from **dunst** to send a notification.

## 99-batify.rules
### Requires
- xpub

### What it Does
Send notifications about laptop battery: 
- When plug/unplug on power supply.
- When battery is low.
