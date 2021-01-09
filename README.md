# [Monitor_brightness_Mangager](https://github.com/arashph17/External_monitor_brightness)
## Welcome :sunglasses:
<img src="pic3.png" height="300">

### External monitor brightness Mangager
<br />
If you added an External monitor to your laptop and the shortcut key for changing brightness on your laptop didn't work, then this script will be helpful for you (of course you need to have a GNU/LINUX distribution)

Put 'screen' in the /usr/bin or /bin or any dir in your PATH. <br />
## Requirements
Notify-send and xrandr. <br />
You most likely have notify-send(99%), but if you don't (that you have :neutral_face:) then install that. <br />
```
which notify-send
```
If printed anything, you have that, Ex. /usr/bin/notify-send
Also you have xrandr probably but if you don't: <br />
#### Debian base:
```
sudo apt install xrandr
```
#### RHEL base:
```
sudo dnf install xrandr
```
#### Arch base:
```
sudo pacman install xrandr
```

After that you can use:
```
screen up
or
screen down
```
Of course this is not useful enough, We want to add shortcut for that.

<img src="pic4.png" height="300">
<br />
### KDE Plasma Desktop
<br />
1. Lunch setting <br />
2. Shortcuts tab <br />
3. Custom Shortcuts <br />
4. Edit, New, Global Shortcut, Command/URL <br />
5. add action (once 'screen up' and once again 'screen dow') <br />
6. add you favrite shortcut (in Trigger tab) <br />
7. add comment :neutral_face:
