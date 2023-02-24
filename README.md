

```


   ██████╗  ██████╗ ████████╗███████╗██╗██╗     ███████╗███████╗
   ██╔══██╗██╔═══██╗╚══██╔══╝██╔════╝██║██║     ██╔════╝██╔════╝
   ██║  ██║██║   ██║   ██║   █████╗  ██║██║     █████╗  ███████╗
   ██║  ██║██║   ██║   ██║   ██╔══╝  ██║██║     ██╔══╝  ╚════██║
   ██████╔╝╚██████╔╝   ██║   ██║     ██║███████╗███████╗███████║
   ╚═════╝  ╚═════╝    ╚═╝   ╚═╝     ╚═╝╚══════╝╚══════╝╚══════╝



 
  i3-gaps        > tiling window manager
  zsh            > shell
  ohmyzsh        > managing zsh configuration
  vscode         > text editor
  firefox        > browser 
  picome         > composite manager 
  spotify        > music player
  thunar         > file manager
  alacritty      > terminal emulator 
  feh            > set wallpaper 
  rofi           > application launcher
  polybar        > status bars
  lxappearance   > theme switcher for GTK+ 
  maim           > screenshot
  flameshot      > screenshot

                               

```

# Preview
![blank](https://github.com/Talfaza/dots/blob/main/screenshot/Fri%20Feb%2024%2003:13:40%20AM%20+01%202023.jpg)
![terminal](https://github.com/Talfaza/dots/blob/main/screenshot/Fri%20Feb%2024%2001:40:21%20AM%20+01%202023.jpg)
![rofi](https://github.com/Talfaza/dots/blob/main/screenshot/2023-02-24_03-12.png)

![code&&thunar](https://github.com/Talfaza/dots/blob/main/screenshot/Fri%20Feb%2024%2001:40:29%20AM%20+01%202023.jpg)

# Theme 




 - [arc-theme](https://github.com/horst3180/arc-theme)

![arc](https://camo.githubusercontent.com/bc506ad41edb5d7e5b851de839838d69719dfe4476b9d417aa0912bb811e5bdf/687474703a2f2f692e696d6775722e636f6d2f3541476c436e412e706e67)

 - [Alacaritty Theme](https://github.com/Talfaza/dots/blob/main/.config/alacritty/alacritty.yml "Alacaritty Theme")
 
 ![alacritty](https://github.com/Talfaza/dots/blob/main/IMG_20230224_025323.jpg)
[ - Rofi Theme](https://github.com/Talfaza/dots/blob/main/.config/rofi/config.rasi " - Rofi Theme")
 ![rofi](https://github.com/Talfaza/dots/blob/main/IMG_20230224_031647.png)
 
 - Visual Studio Code Theme : [SynthWave '84](https://marketplace.visualstudio.com/items?itemName=RobbOwen.synthwave-vscode)
 ![vscode](https://www.nikouusitalo.com/content/images/size/w2000/2021/10/Header.png)
# Packages 

## Terminal

- Alacritty : 

Installation :

```sh
sudo add-apt-repository ppa:aslatter/ppa && sudo apt update && sudo apt install alacritty 
```

- ZSH : 
```sh
sudo apt install zsh
```
- Ohmyzsh : 
```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```


## i3-gaps
```sh
sudo apt purge i3
```

```sh
sudo apt install meson dh-autoreconf libxcb-keysyms1-dev libpango1.0-dev libxcb-util0-dev xcb libxcb1-dev libxcb-icccm4-dev libyajl-dev libev-dev libxcb-xkb-dev libxcb-cursor-dev libxkbcommon-dev libxcb-xinerama0-dev libxkbcommon-x11-dev libstartup-notification0-dev libxcb-randr0-dev libxcb-xrm0 libxcb-xrm-dev libxcb-shape0 libxcb-shape0-dev
```

```sh
git clone https://github.com/Airblader/i3 i3-gaps
```
```sh
cd i3-gaps
```
```sh
mkdir -p build && cd build
```
```sh
meson --prefix /usr/local
```

```sh
ninja
```
```sh
sudo ninja install
```



