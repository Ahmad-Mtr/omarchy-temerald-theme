# Omarchy Temerald Theme

![preview.png](preview.png)


## TODOS
- [x] use lutgen to create more bgs
- [x] Preview
- [ ] complete other terminals UI 
- [ ] finish vscode theme
- [ ] include color palette + desc
- [ ] finish nvim theme 
- [ ] customize waybar

## Installation
To install on Omarchy:
```sh
omarchy-theme-install https://github.com/Ahmad-Mtr/omarchy-temerald-theme
```

## Wallpapers
- psst, I have a [personal wallpapers repo](https://github.com/Ahmad-Mtr/wallpapers) that has both Temerald & Catppuccin wallpapers, almost all edited with [Lutgen](https://github.com/ozwaldorf/lutgen-rs) 
- I've included only 5 Walls in `backgrounds/`, add more on your own
- Hald clut image is included, incase you want to edit other images to use Temerald, instructions below

### Make your own Wallpapers
- requires lutgen installed

```bash
lutgen apply --hald-clut temerald-hald-clut-v2.png <list-of-wallpapers-to-be-edited>
```



## Included configs
- Alacritty (alacritty.toml)
- btop (btop.theme)
- Hyprland (hyprland.conf, hyprlock.conf)
- Mako (mako.ini)
- Neovim (neovim.lua) `note: using temporarily Poimanders theme`
- Vscode (vscode.json) `note: same as neovim`
- Waybar (waybar.css)
- Wofi (wofi.css)
- Walker (walker.css)
- SwayOSD (swayosd.css)



## Credits 
- Customized the Theme via [Omarchist](https://github.com/tahayvr/omarchist)
- Took some Inspiration from [Poimanders](https://github.com/drcmda/poimandres-theme) 
- Modifying Wallpapers to match theme with [lutgen](https://github.com/ozwaldorf/lutgen-rs) 

- 

## License
MIT
