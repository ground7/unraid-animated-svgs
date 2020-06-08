# Animated Docker Folder Icons for Unraid
[![License](https://img.shields.io/github/license/ground7/unraid-animated-svgs)](./LICENSE.md)
![Downloads](https://img.shields.io/github/downloads/ground7/unraid-animated-svgs/total.svg)

**Please Note** that only the always-animate variant works with the docker folder plugin as of the most recent release. I'll be leaving animate-on-hover up in case anyone wants to use them in another application where hovering works as intended.

## Collection
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/audio.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/backup.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/binoculars.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/code.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/database.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/eye.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/home-wifi.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/multimedia-alternate.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/vpn.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/world.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/control.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/multimedia.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/music.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/nzb.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/pirate.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/search.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/security.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/settings.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/ship.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/torrent.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/cloud.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/dash.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/dependencies.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/downloads.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/gaming.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/grafana.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/home-automation.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/network.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/plex.svg" width="85" height="85">]()
[<img src="https://raw.githubusercontent.com/ground7/unraid-animated-svgs/master/Always%20Animate/productivity.svg" width="85" height="85">]()

## How to Tweak
To change a color look for
```xml
fill="####"
```
and switch the number to the desired 6-digit RGB hex code.

For more complicated tweaks that don't affect the animation, I suggest using [inkscape](https://github.com/inkscape/inkscape). Be careful to not change the groupings or the animation will break. Inkscape will add a lot of useless metadata to the svg after saving. If you'd like to clean it up, I suggest using [svgocd](https://github.com/Shtian/vscode-svgocd) with [this yaml](https://github.com/ground7/unraid-animated-svgs/blob/master/.svgo.yml).

## Requests
I am currently taking requests for icons to be animated. If you'd like me to animate an svg icon fill out the following issue template.

### Issue Template:
```
Folder Category: <what is this a category for?>
Animation Suggestion: <your animation idea>
File: <attach a zip file with the svg>
```

### Additional Notes
Please check if there's already a satisfactory icon covering the category. If you don't like it, you can still suggest another one.

In addition, I'm only animating svgs with css. Making them from scratch can be a decent amount of work too, so please make the actual svg yourself. Make sure to layer the svg appropriately if the animation requires it. Svgs can be created pretty easily with the free tool inkscape, and they are often an export option on image editors. Some websites can convert to them as well with varying degrees of success. [Hernadito](https://github.com/hernandito) is also taking requests on the [Unraid forum](https://forums.unraid.net/topic/92824-icon-collections-for-docker-folder-plugin/).

## Credits
- Thank you [Hernadito](https://github.com/hernandito) for creating initial svgs for me to work off of. You can check out his color variations of this icon set [here](https://github.com/hernandito/unRAID-Docker-Folder-Animated-Icons---Alternate-Colors).
- Thank you [GuildDarts](https://forums.unraid.net/profile/80260-guilddarts/) for your work on the Unraid Docker Folders plug-in which inspired all this work.
