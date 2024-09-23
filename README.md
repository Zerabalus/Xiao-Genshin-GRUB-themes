## 🔖 Contents

<a><img src="https://64.media.tumblr.com/65c422a3b1b84f50649d239f3f8ce18e/1a269cdcb80f405b-d0/s500x750/e2453746d023cdcec190021b208e7621d2d341f9.gifv" width="40%" title="🙂" align="right"></a>

- <b>[🖥️ GRUB Themes](#grub-themes)</b>

  - [💚 Xiao (Genshin Impact)](#grub-themes)
    - [Eng ver.](#art-preview-theme-)

- <b>[🔧 Installation](#installation)</b>
  - [First method](#1-installation)
  - [Second method (wip script, soon)](#2-installation)

<a><img src="https://64.media.tumblr.com/0d8a45287d985a9db7ee02c7fe4f490e/722f0b3a5709c1b2-f0/s640x960/7fd87a295114072f54e995704776527c24f05aa2.gifv" width="40%" title="🙂" align="right"></a>

## :Installation
### : <b>1. Installation</b>

- Open your terminal
- Copy the repository and unzip
```
    git clone https://github.com/Zerabalus/GRUB-THEMES.git
```

- Using Xiao Grub as an example:

- cd to where you copied it, on your terminal:
```
sudo cp -r Xiao /usr/share/grub/themes
```

- Or like in my case
```
sudo cp -r Xiao /boot/grub/themes
```

- Then edit the name of the grub theme you want:
```
sudo nano /etc/default/grub
```
```
GRUB_THEME="/boot/grub/themes/Xiao/theme.txt"
```
- Update the grub
```
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

- Reboot your pc
```
reboot
```
