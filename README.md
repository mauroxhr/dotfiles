<h1 align="center">dotfiles  ~/</h1>


![xhlar dotfiles](https://i.imgur.com/b579XZG.png)

# Introduction
Configuration files

# How to install dotfiles
1. chmod +x install.sh
2. ./install.sh -i

# How to install nvim 
0. cd .nvim 
1. git submodule init
2. git submodule update

# How to install plugins for oh my zsh
1. ./install.sh -p

# How to install dependencies 
The script detected your distribution and install dependencies and programs. 

1. chmod +x install.sh
2. ./install.sh -p

# Test this dotfiles with docker
1. docker build -t dotfiles .
2. docker run -it dotfiles
3. apt update && apt install git
5. ./install.sh -h 




## Main programs

- [i3](https://github.com/i3/i3) - A tiling window manager.
- [i3-gnome](https://github.com/i3-gnome/i3-gnome) - Use i3wm/i3-gaps with GNOME Session infrastructure.
- [i3lock](https://github.com/i3/i3lock) - improved screen locker
- [Rofi](https://github.com/davatorium/rofi) - A window switcher, application launcher and dmenu replacement.
- [fzf](https://github.com/junegunn/fzf) - A command-line fuzzy finder.
- [nvim](https://github.com/NvChad/NvChad) - Blazing fast Neovim config providing solid defaults and a beautiful UI, enhancing your neovim experience.
- [lazyvim](https://github.com/jesseduffield/lazygit) - simple terminal UI for git commands
- [btop](https://github.com/aristocratos/btop) - A monitor of resources
- [Zsh](https://github.com/zsh-users/zsh) - A shell designed for interactive use, although it is also a powerful scripting language.
- [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh) - An open source, community-driven framework for managing your Zsh configuration.
- [z](https://github.com/rupa/z) - Tracks your most used directories, based on frecency.
- [Git](https://github.com/git/git) - A free and open source distributed version control system.
- [Gnome Terminal](https://github.com/GNOME/gnome-terminal) - A cross-platform, GPU-accelerated terminal emulator.
- [exa](https://github.com/ogham/exa) - A modern replacement for ls
- [Font Awesome](https://github.com/FortAwesome/Font-Awesome) - Iconic font.
- [picom](https://github.com/yshui/picom) - A lightweight compositor for X11.

## Dependencies
- [xcwd](https://github.com/schischi/xcwd) - A simple tool that prints the current working directory of the currently focused window
- [libx11-devel](https://packages.fedoraproject.org/pkgs/libX11/libX11-devel/) - Development files for libX11

## Laptop
- [i3-battery-popup](https://website.org/) - pop up battery
- [i3blocks](https://github.com/vivien/i3blocks) - A feed generator for text based status bars.
- [i3blocks-contrib](https://github.com/vivien/i3blocks-contrib) - A set of scripts for i3blocks, contributed by the community.
- [arandr](https://github.com/) - xrandr gui
- [Arc Theme](https://github.com/arc-design/arc-theme) (Fork) - A flat theme with transparent elements for GTK 3, GTK 2, and GNOME Shell.
- [Dark Planet](https://www.pling.com/p/1163924/) - Wallpaper.

---
## List of programs 

- [coinomi](https://www.coinomi.com/) - Coinomi desktop wallet. Securely store, manage and exchange Bitcoin, Ethereum, and more than 500 other blockchain assets
- [electrum](https://electrum.org/) - Lightweight Bitcoin wallet 
- [seahorse](https://aur.archlinux.org/packages/seahorse-git) - GNOME application for managing encryption keys and passwords in the GNOME Keyring.
- [keepassxc](https://keepassxc.org/) - Cross-Platform Password Manager
- [veracrypt](https://www.veracrypt.fr/code/VeraCrypt/) - a free and open-source utility for on-the-fly encryption.
- [pavucontol](https://freedesktop.org/software/pulseaudio/pavucontrol/) - PulseAudio Volume Control (pavucontrol) is a simple GTK based volume control tool ("mixer") for the PulseAudio sound server
- [qbittorrent](https://www.qbittorrent.org/) - a cross-platform free and open-source BitTorrent client.
- [balena-etcher](https://www.balena.io/etcher/) - Flash OS images to SD cards & USB drives
- [ventoy](https://www.ventoy.net/en/index.html) - Ventoy is an open source tool to create bootable USB drive for ISO/WIM/IMG/VHD(x)/EFI file
- [clonezilla](https://clonezilla.org/) - A partition and disk imaging/cloning program which helps with system deployment, bare metal backup and recovery
- [ncdu](https://dev.yorhel.nl/ncdu) -  a disk usage analyzer with an ncurses interface
- [freetube](https://github.com/FreeTubeApp/FreeTube) - an open source desktop YouTube player built with privacy in mind.
- [drawio](https://app.diagrams.net/) - Flowchart Maker & Online Diagram Software
- [ifuse](https://github.com/libimobiledevice/ifuse) - A fuse filesystem implementation to access the contents of iOS devices
- [gnome-books](https://launchpad.net/ubuntu/+source/gnome-books) - ebook reader 
- [gnome-todo](https://gitlab.gnome.org/GNOME/gnome-todo) - a personal task manager made to perfectly fit the GNOME desktop
- [gnome-clocks](https://gitlab.gnome.org/GNOME/gnome-clocks) - a simple application to show the time and date in multiple locations and set alarms or timer
- [gnome-pomodoro](https://github.com/gnome-pomodoro/gnome-pomodoro) - A time management utility for GNOME based on the pomodoro technique!
- [gnome-terminal](https://archlinux.org/packages/extra/x86_64/gnome-terminal/) - The GNOME Terminal Emulator
- [dijo](https://github.com/nerdypepper/dijo) - scriptable, curses-based, digital habit tracker
- [geogebra](https://geogebra.org/) - an interactive geometry, algebra, statistics and calculus application, intended for learning and teaching mathematics
- [kile](https://kile.sourceforge.io/) - TeX/LaTeX editor to edit TeX/LaTeX source code
- [libreoffice](https://www.libreoffice.org/) -  free and open-source office productivity software suite
- [zoom](https://zoom.com) -  videotelephony software program
- [dropbox](https://dropbox.com) - file hosting service 
- [thunderbird](https://www.thunderbird.net/) - free and open-source cross-platform email client
- [ghostwriter](https://wereturtle.github.io/ghostwriter/) - Markdown Writer 
- [pcmanfm](https://github.com/lxde/pcmanfm) - Extremely fast and lightweight file manager
- [xarchiver](https://archlinux.org/packages/community/x86_64/xarchiver/) - frontend to various command line archivers
- [CutyCapt](https://github.com/amw/CutyCapt) - capture Webkit's rendering of a web page, and save that rendering as either SVG, PDF, PS, PNG, JPEG, TIFF, GIF, or BMP files

## Programming
- [staruml](https://staruml.io/) - a sophisticated software modeler aimed to support agile and concise modeling
- [sqlitestudio](https://sqlitestudio.pl/) - Create, edit, browse SQLite databases.
- [mysql-workbench](https://www.mysql.com/products/workbench/) - a visual database design tool that integrates SQL development, administration, database design, creation and maintenance into a single integrated development environment for the MySQL 
- [docker](https://www.docker.com/) - a set of platform as a service products that use OS-level virtualization to deliver software in packages called containers.
- [docker-compose](https://docs.docker.com/compose/install/) - Compose is a tool for defining and running multi-container Docker applications.
- [virtualbox](https://www.virtualbox.org/) - cross-platform virtualization software.
- [zeal](https://www.zealdocs.org/) - Zeal is an offline documentation browser for software developers.

# Typing
- [espanso](https://github.com/espanso/espanso) - Cross-platform Text Expander written in Rust 

## Presentation and content creation
- [rclone](https://github.com/rclone/rclone) - is a command-line program to sync files and directories to and from different cloud storage providers.
- [uxplay](https://github.com/antimof/UxPlay) - dAirPlay Unix mirroring server
- [phonepresenter](https://phonepresenter.github.io/) - Control presentations from your smartphone
- [obs](https://github.com/obsproject/obs-studio) - Free and open source software for live streaming and screen recording- 
- [peek](https://github.com/phw/peek) - Simple animated GIF screen recorder with an easy to use interface. 
- [kdenlive](https://github.com/KDE/kdenlive) - Free and open source video editor.
- [asciinema](https://asciinema.org/) - Record and share your terminal sessions, the simple way.
- [gimp](https://github.com/GNOME/gimp) - Open souce image editor 
- [pinta](https://github.com/PintaProject/Pinta) - Simple GTK Paint Program
- [screenkey](https://github.com/wavexx/screenkey) - A screencast tool to display your keys inspired by Screenflick
- [gromit-mpx](https://github.com/bk138/gromit-mpx) - an on-screen annotation tool that works with any Unix desktop
- [audacity](https://github.com/audacity/audacity) - Audio Editor

---
 # Thanks to...
- [Dikiaap](https://github.com/dikiaap) and his [dotfiles](https://github.com/dikiaap/dotfiles)
