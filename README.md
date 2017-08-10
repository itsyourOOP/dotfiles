# Dotfiles for Arch
Theming based on [wal](https://github.com/dylanaraps/pywal) for automated coloring of everything.  
In ranger use 'mkt' on image to have colorscheme generated and applied to everything. 
Manual firefox restart currently necessary for [userChrome.css](.config/userChrome.css) to be applied.

**Shell:** [zsh](https://github.com/zsh-users/zsh)  
**Terminal emulator:** [urxvt](https://github.com/exg/rxvt-unicode)  
**Terminal multiplexer:** [tmux](https://github.com/tmux/tmux)  
**WM:** [i3-gaps](https://github.com/Airblader/i3)  
**Bar:** [polybar](https://github.com/jaagr/polybar)  
**Launcher:** [rofi](https://github.com/DaveDavenport/rofi)  
**Text editor:** [vim](https://github.com/vim/vim)  
**Notification daemon:** [dunst](https://github.com/dunst-project/dunst)  
**File manager:** [ranger](https://github.com/ranger/ranger)  
**Media player:** [mpv](https://github.com/mpv-player/mpv)  
**Music:** [mopidy](https://github.com/mopidy/mopidy) with [mopidy-spotify](https://github.com/mopidy/mopidy-spotify) and [ncmpcpp](https://github.com/arybczak/ncmpcpp)  
**Visualizer:** [cava](https://github.com/karlstav/cava)  
**System info:** [neofetch](https://github.com/dylanaraps/neofetch)  
**Screenlocker:** [i3lock](https://github.com/i3/i3lock)  
**Screenshot utility:** [maim](https://github.com/naelstrof/maim)  
**Browser:** Firefox  
**Startpage:** [startpage](https://github.com/ecly/startpage)

**Additional dependencies:**
- [pulseaudio](https://www.archlinux.org/packages/?name=pulseaudio) & [pulseaudio-alsa](https://www.archlinux.org/packages/extra/any/pulseaudio-alsa/), alsa version is necessary for polybar volume.
- [w3m](http://w3m.sourceforge.net/), for previews in ranger.
- [Iosevka](https://github.com/be5invis/Iosevka), font used for basically everything.

**Manual setup:**
- Manual symlinking of [userChrome.css](.config/userChrome.css) to Firefox profile upon clone.
- Manual clone and setup of [startpage](https://github.com/ecly/startpage) with Firefox.
- Mopidy spotify authorization configuration & renaming of config file.