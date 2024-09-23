## 🍃 Contents 🍃

<a><img src="https://i.pinimg.com/originals/31/26/51/3126516d77b2f81eb31c088f605b2378.gif" width="30%" height="40%" title="🙂" align="right"></a>
<br/><br/>

- <b>[🖥️ GRUB Themes](#grub-themes)</b>

  - [💚 Xiao (Genshin Impact)](#grub-themes)
    - [Eng ver.](#art-preview-theme-)

- <b>[🔧 Installation](#installation)</b>
  - [First method](#1-installation)
  - [Second method (wip script, soon)](#2-installation)



## Installation
### <b>1.</b>
<a><img src="https://i.pinimg.com/originals/45/3d/87/453d874a5cb24f5321162400c0eb5262.gif" width="30%" height="30%" title="🙂" align="right"></a>
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
