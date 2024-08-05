# Dependencies

`pacman -S swaync hyprpaper hyprlock font-manager blueman nwg-look rofi fastfetch nemo nemo-fileroller nvidia-prime rhythmbox nvidia-utils lib32-nvidia-utils playerctl`

`yay -S ttf-font-awesome visual-studio-code-bin hyprpicker hyprshot kdeconnect sshfs`

## Yay install

`pacman -S --needed git base-devel && git clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si`

or precompiled binary

`pacman -S --needed git base-devel && git clone https://aur.archlinux.org/yay-bin.git && cd yay-bin && makepkg -si`



# Other apps

Steam:

Enable `multilib` repository

`pacman -S steam`



# Keybinds

|        Keybind        |                  Action                  |
| --------------------- | ---------------------------------------- |
| `Win + R`             | Launch Run Menu (rofi)                   |
| `Win + Q`             | Open Terminal (kitty)                    |
| `Win + E`             | Open File Explorer (nemo)                |
| `Win + X`             | Open Cava                                |
| `Win + C`             | Open Visual Studio Code                  |
| `Win + V`             | Toggle Window Float                      |
| `Win + 1-9`           | Switch to Workspace 1-9                  |
| `Win + CTRL + Left`   | Previous Workspace                       |
| `Win + CTRL + Right`  | Next Workspace                           |
| `Win + SHIFT + 1-9`   | Move Active Window to Workspace 1-9      |
| `Win + W`             | Close Active Window                      |
| `Win + ALT + Left`    | Previous Song (playerctl -p rhythmbox)   |
| `Win + ALT + Right`   | Next Song (playerctl -p rhythmbox)       |





# Credits/Sources:

[1amSimp1e - Late Night](https://github.com/1amSimp1e/dots)

[Catppuccin](https://github.com/catppuccin)

[PowerLevel10k](https://github.com/romkatz/powerlevel10k)

[OhMyZsh](https://github.com/ohmyzsh/ohmyzsh)

[Cava](https://github.com/karlstav/cava)
