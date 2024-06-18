### Quickstart

To setup kitty

```console
mkdir -p ~/.config/kitty/themes
cp ./kitty/BreakingBad.conf ~/.config/kitty/themes/
cp ./kitty/kitty.conf ~/.config/kitty/kitty.conf
kitty +kitten themes --reload-in=all "Breaking Bad"
```

To setup rofi

```console
mkdir -p ~/.config/rofi/themes
cp ./rofi/breaking-bad.rasi ~/.config/rofi/themes/
cp ./rofi/config.rasi ~/.config/rofi/config.rasi
```

To setup i3

```console
mkdir -p ~/.config/i3
cp ./i3/config ~/.config/i3/config
```

To setup i3status-rust

```console
mkdir -p ~/.config/i3status-rust
cp ./i3status-rust/config.toml ~/.config/i3status-rust/config.toml
```

Recommended to use with <https://github.com/alexjercan/nvim.dotfiles>
