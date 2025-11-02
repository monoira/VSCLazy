# VSCLazy

- [VSCLazy](#vsclazy)
  - [Symlink global settings.json file for keybindings](#symlink-global-settingsjson-file-for-keybindings)
  - [keybindings](#keybindings)

Visual Studio Code DISTRO With:

- Vim Extension
- [LazyVim like global keybindings](https://www.lazyvim.org/keymaps#bufferlinenvim)
- Github Copilot & Copilot Chat Extensions

other sensible defaults For Maximum Productivity.

## Symlink global settings.json file for keybindings

In my case, I save dotfiles at `~/.dotfiles`, which is managed with `git` and `stow`.

```bash
ln -sf "$HOME/.dotfiles/vscode/settings.json" $HOME/.config/Code/User/settings.json
```

## keybindings

| Keybinding     | Feature                    |
| -------------- | -------------------------- |
| `<Leader>+f+p` | Find Projects (Workspaces) |
