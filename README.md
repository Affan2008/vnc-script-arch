# vnc-script-arch
Somewhat simple and not so useful vnc script

Kinda obselete, requires TigerVNC 1.10.1 which no longer seem to work on x86_64 systems due to missing libraries.
Currently tested to work on ArchLinuxARM (chroot).

# Installation
Firstly, install the ```git``` package

```pacman -S git```

Clone this git repo

```git clone https://github.com/Affan2008/vnc-script-arch.git```

Change some premissions

```cd vnc-script-arch/vnc && chmod +x vnc && chmod +x start/* && chmod +x gui/*```

Copy all files to ```/usr/local/bin```

```cd && cd vnc-script-arch/vnc && cp -r * /usr/local/bin```

Now you can launch vnc server using

```vnc <window_manager>```

This thing currently supports some popular window manager and desktop environments.
For example: Fluxbox, MATE, Openbox, i3, awesome, LXDE, Enlightenment, XFCE

Full list of options and supported window managers/desktop environments coming soon... 
