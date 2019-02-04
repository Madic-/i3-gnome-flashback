# i3 Molokai with gome-flashback

Why gnome-flashback? Because it does support me with the sound, display and bluetooth configuration and supports thinks like dynamically changing the display in case I take my notebook out of the docking station.

## Current setup

* **OS:** Fedora 29
* **Shell:** Bash
* **WM:** i3-gaps with gnome-flashback
* **Bar:** i3blocks
* **Theme:** Molokai
* **Terminal:** gnome-terminal
* **GTK:** [Windows 10](https://www.gnome-look.org/p/1013482/)
* **Icons:** [Windows 10](https://github.com/B00merang-Artwork/Windows-10)

## Installation

Run setup.sh. During installation it will do the following changes to the system:

* Add the following repos from fedora copr:

⋅⋅* (pkgbot/pkgs)[https://copr.fedorainfracloud.org/coprs/pkgbot/pkgs/] for the i3 environment

⋅⋅* (victoroliveira/gnome-flashback)[https://copr.fedorainfracloud.org/coprs/victoroliveira/gnome-flashback/] for gnome-flashback

* Install required software (see setup.sh for details)

* Install (csxr's i3-gnome)[https://github.com/csxr/i3-gnome] integration

* Files from the config folder will be symlinked to the appropriate location

* i3block scripts will be downloaded from (i3-contrib repository)[https://github.com/vivien/i3blocks-contrib] to ~/.config/i3/scripts

* Add entries to /root/.bashrc and ~/.bashrc

The GTK Theme and Icons need to be manually downloaded
