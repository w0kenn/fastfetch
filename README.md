# w0keNN Fastfetch

### Welcome to my fastfetch preset repository

[Fastfetch](https://github.com/fastfetch-cli/fastfetch) is a tool for fetching system information and displaying it in a visually appealing way. This repo contains my personal config made for [Kitty](https://sw.kovidgoyal.net/kitty/) which is a GPU based terminal emulator, that means this terminal emulator is fast and capable to show emojis and images, so feel free to use it, copy things and modify it to make it YOURS.

![Example image](screenshots/exampleimage.png)
---
### Requirements
>This is not a standalone, for it to work properly you'll need to install:
- [Fastfetch](https://github.com/fastfetch-cli/fastfetch)
- [Kitty](https://sw.kovidgoyal.net/kitty/) (if you don't have a GPU based Terminal emulator, you will not be able to see the .png logos).
- [Nerd Font](https://www.nerdfonts.com/font-downloads) (without this the icons won't show).

### Installation guide

**1. Install Fastfetch: The following table shows base distros, the cmd works for their fork distros too.**

| Distribution | Terminal Command |
| ------------ | ---------------- |
| Arch         | sudo pacman -Sy fastfetch |
| Debian / Ubuntu | sudo apt install fastfetch |
| Fedora | sudo dnf install fastfetch |

**2. Install a Nerd Font: This config uses Nerd Font icons. Without one you'll see empty boxes.**

> The screenshot font is "Hack Nerd Font".

- Create a `fonts` directory into `~/.local/share`: 

```
mkdir -p ~/.local/share/fonts

```
- Visit the [Nerd Font](https://www.nerdfonts.com/font-downloads) website and download the one you like the most, unzip it and copy every `.ttf` and `.otf` inside the `~/.local/share/fonts` directory you made.
- Run:

```
fc-cache -fv
```

**3. Clone the repository into `~/.config/fastfetch`:**
```
git clone https://github.com/w0kenn/fastfetch ~/.config/fastfetch
```
Then run it with:
```
fastfetch
```
