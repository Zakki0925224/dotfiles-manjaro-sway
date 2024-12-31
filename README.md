# dotfiles-manjaro-sway

## Usage

```bash
cd ~
git clone https://github.com/Zakki0925224/dotfiles-manjaro-sway.git
mkdir -p dotfiles-backup/.config
mv .bashrc .profile .zshenv .zshrc ./dotfiles-backup
mv .config/sway ./dotfiles-backup/.config/sway
mv .config/waybar ./dotfiles-backup/.config/waybar
ln -s ./dotfiles-manjaro-sway/.bashrc .bashrc
ln -s ./dotfiles-manjaro-sway/.profile .profile
ln -s ./dotfiles-manjaro-sway/.zshenv .zshenv
ln -s ./dotfiles-manjaro-sway/.zshrc .zshrc
ln -s ../dotfiles-manjaro-sway/.config/sway .config/sway
ln -s ../dotfiles-manjaro-sway/.config/waybar .config/waybar
```
