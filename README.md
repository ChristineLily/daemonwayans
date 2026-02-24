# DaemonWayans 1.0.0
## A lightweight daemon written in Go. Checks if the AUR is up.

Not in any way affiliated with noted polytalent Damon Wayans
or any of the Wayans clan for that matter...this is just a daemon.

![Noted Polytalent Damon Wayans](damon_wayans.jpg "The real Damon Wayans")

### Roadmap
~~- Add icon/uptime indicator to notification area/systray~~

~~- Create package for AUR~~


### Planned Future Features
- Downtime indicator (rather than the app just Exiting)
- Menu Tray item that quits the daemon
- 

---

Hello, fellow Arch distro users! You know when you go to install something with yay or paru and it's not working so you get confused and the error code is vague so you get frustrated before you finally decide to ping the AUR only to find out that the AUR is DOWN because of a malicious DDoS attack?! (Yes, this did actually happen.)

Specificity aside, idk yo. It's an observer daemon that watches the AUR.

If it's up, you'll see a Wayans (in your systray).
If it's down, you won't see a Wayans.
If you don't see a Wayans, restart the daemon. Repeat as necessary. (Or just ping the AUR)

AUR Package: https://aur.archlinux.org/packages/daemonwayans

After installing, you'll need to make a .service file so you can tell systemd to run it at startup.
Instructions for how to do this are readily findable via search engine and beyond the scope of this README.
