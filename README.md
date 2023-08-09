# Arch Hyprland Configuration

```sh
sudo pacman -S --needed base base-devel git neovim curl wget ffmpeg foot fzf gcc grim gtk2 gtk3 gkt4 httpie jq hyprland kitty nemo neofetch obs-studio obsidian ripgrep rofi zsh starship tmux trash tree zoxide
```
```sh
git clone https://aur.archlinux.org/yay-git.git
cd yay
makepkg -si
cd ..
rm -rf yay-git
```

```sh
yay -S extra/bat extra/btop aur/cava aur/nwg-look aur/nvchad aur/spotify-adblock aur/swww aur/swaylock-effects aur/swaync aur/waybar-hyprland-git aur/google-chrome 
```

```sh
yay -S catppuccin-gtk-theme-mocha catppuccin-gtk-theme-macchiato catppuccin-gtk-theme-frappe catppuccin-gtk-theme-latte dracula-icons-git
```

```sh
git clone https://github.com/sbadung/hyprland-dotfiles.git 
cp hyprland-dotfiles/.config/* $HOME/.config
cp hyprland-dotfiles/.zshrc hyprland-dotfiles/.zsh hyprland-dotfiles/.gtkrc-2.0 $HOME 
rm -rf hyprland-dotfiles
```
