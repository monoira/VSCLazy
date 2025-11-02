# VSCLazy

- [VSCLazy](#vsclazy)
  - [HOW](#how)
  - [KEYBINDINGS](#keybindings)

Visual Studio Code DISTRO With:

- Vim Extension
- [LazyVim like global keybindings](https://www.lazyvim.org/keymaps#bufferlinenvim)
- Github Copilot & Copilot Chat Extensions

And more sensible defaults For Maximum Productivity and Comfort.

```bash
├── profiles
│   └── prof.code-profile
├── settings.json
└── workspaces
    └── PLACE YOUR WORKSPACES HERE
```

## HOW

1. Clone `VSClazy` directory in your dotfiles.
1. Remove `.git`.
1. Import `prof` profile from [profiles/prof.code-profile](profiles/prof.code-profile).
1. Symlink global settings.json file for keybindings.  
   In my case, I save dotfiles at `~/.dotfiles`, which is managed with `git` and `stow`.

```bash
ln -sf "$HOME/.dotfiles/VSCLazy/settings.json" $HOME/.config/Code/User/settings.json
```

## KEYBINDINGS

| Keybinding     | Feature                          |
| -------------- | -------------------------------- |
| `<C-u>`        | Scroll up half page and center   |
| `<C-d>`        | Scroll down half page and center |
| `g d`          | Go to definition                 |
| `g D`          | Go to declaration                |
| `g I`          | Go to implementation             |
| `g r`          | Go to references                 |
| `g y`          | Go to type definition            |
| `K`            | Show hover info                  |
| `g K`          | Show parameter hints             |
| `] d`          | Next diagnostic                  |
| `[ d`          | Previous diagnostic              |
| `] e`          | Next error                       |
| `[ e`          | Previous error                   |
| `] w`          | Next warning                     |
| `[ w`          | Previous warning                 |
| `[ b`          | Previous editor tab              |
| `] b`          | Next editor tab                  |
| `[ B`          | Move editor left                 |
| `] B`          | Move editor right                |
| `<leader> b d` | Close current editor             |
| `<leader> b r` | Close editors to the right       |
| `<leader> b l` | Close editors to the left        |
| `<leader> b o` | Close all other editors          |
| `<leader> e`   | Focus file explorer              |
| `<leader> s d` | Toggle problems panel            |
| `<leader> s k` | Open command palette             |
| `<leader> s r` | Replace in files                 |
| `<leader> s s` | Go to symbol in file             |
| `<leader> s S` | Go to symbol in workspace        |
| `<leader> /`   | Quick text search                |
| `<leader> f p` | Open recent projects             |
| `<leader> f r` | Open recent files                |
| `<leader> f f` | Quick open file                  |
| `<leader> g g` | Focus source control             |
| `<leader> c a` | Quick fix                        |
| `<leader> c A` | Source action                    |
| `<leader> c r` | Rename symbol                    |
| `<leader> c p` | Preview markdown                 |
| `<leader> c u` | Remove unused imports            |
