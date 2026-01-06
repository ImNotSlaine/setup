# NAS Setup

## System Information

* CPU: Intel Celeron G3220 @ 3.00 GHz
* RAM: 8 GB
* GPU: Integrated Intel
* OS: Debian Trixie

## Initial Install

* Installed `sudo apt install ufw openssh smb nfs-kernel-server`.
* `ufw allow smb` `ufw allow nfs` `ufw allow ssh` `ufw enable`.
