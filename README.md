# Arch Linux Configuration

Install a flurry of packages from the official registry

```
$ pacman -Syu bspwm polybar picom sxhkd alacritty fontconfig ttf-jetbrains-mono-nerd lightdm-gtk-greeter zsh
```
which should cover nearly all of the action. For the others, we have to resort to `yay` which comes in handy every so often.

```
sudo pacman -S --needed git base-devel && git clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si
```

From here, we can install the rest

```
yay -S juliaup neofetch
```
