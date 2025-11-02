# VSCLazy

- [VSCLazy](#vsclazy)
  - [HOW](#how)
  - [KEYBINDINGS](#keybindings)

Visual Studio Code DISTRO With:

- Vim Extension
- [LazyVim like global keybindings](https://www.lazyvim.org/keymaps#bufferlinenvim)
- Github Copilot & Copilot Chat Extensions

And more sensible defaults For Maximum Productivity and Comfort.

## HOW

1. place `VSClazy` directory in your dotfiles.
1. remove `.git`.
1. Import `prof` profile from [profiles/prof.code-profile](profiles/prof.code-profile).
1. Symlink global settings.json file for keybindings.  
   In my case, I save dotfiles at `~/.dotfiles`, which is managed with `git` and `stow`.

```bash
ln -sf "$HOME/.dotfiles/vscode/settings.json" $HOME/.config/Code/User/settings.json
```

## KEYBINDINGS

| Keybinding     | Feature                    |
| -------------- | -------------------------- |
| `<Leader>+f+p` | Find Projects (Workspaces) |
