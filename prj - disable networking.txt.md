###Disable Network - Menubar app

- single click to enable or disable
- similar to log me in - gray/black
- menubar popup to configure which one to disable with one click.

```

sudo ifconfig en0 down
networksetup -setairportpower en1 off

sudo ifconfig en0 up
networksetup -setairportpower en1 on


networksetup -setairportpower en1 off

networksetup -listallhardwareports


```
###Links

https://github.com/shpakovski/Popup


---
2013-04-19