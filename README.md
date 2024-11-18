# Dotfiles
This repo contains my dotfiles for using Sway (i3 on Wayland)

## Deps
Use the `deps.sh` script to install all packages configured by this repo on debian based systems.
#### Neovim
This script will clone the following repo to the Neovim config location. The Neovim config is managed by this enirely seperate repo.
https://github.com/jstrebeck/neovim-config

### Stow
This repo uses `stow` to mange the dot files

Install a config

- This will place the config in correct location for you.

```
stow sway 
```

Remove a config
```
stow -D sway
```

![header image](https://github.com/jstrebeck/Dotfiles/blob/migrate-to-sway/image.png)
