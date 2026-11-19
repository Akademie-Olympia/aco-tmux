# tmux configuration

Portable, modular tmux configuration with themes, a key explorer and optional vendored plugins. The normal tmux features stay reachable.

**[Full documentation](https://aco-tmux.readthedocs.io/en/latest/)** ·
[Arch package](https://aco-tmux.readthedocs.io/en/latest/packages/) ·
[Key bindings](https://aco-tmux.readthedocs.io/en/latest/keybindings/quick/) ·
[Options](https://aco-tmux.readthedocs.io/en/latest/reference/options/) ·
[Design & dependencies](https://aco-tmux.readthedocs.io/en/latest/design/)

```bash
curl -fsSL https://raw.githubusercontent.com/Akademie-Olympia/aco-arch-dotfiles/main/install.sh | bash -s -- tmux
```

Package: `aco-arch-dotfiles-tmux`. Local customisation: `~/.config/tmux/local-options.conf` and `local.conf`. `prefix H` opens the key explorer, `prefix R` reloads.
For tmux 3.8 the extras now live on `prefix G` (scratch terminal), `prefix J` (fetch pane) and `prefix B` (last window) so that `g`, `@` and `Tab` keep their new tmux defaults.
Develop independently in this repository and push to `main`; after a successful registry build update with `sudo pacman -Syu`. Local builds: [PACKAGING.md](PACKAGING.md).

[![CI](https://github.com/Akademie-Olympia/aco-tmux/actions/workflows/ci.yml/badge.svg)](https://github.com/Akademie-Olympia/aco-tmux/actions/workflows/ci.yml)
[![Package safety](https://github.com/Akademie-Olympia/aco-tmux/actions/workflows/package.yml/badge.svg)](https://github.com/Akademie-Olympia/aco-tmux/actions/workflows/package.yml)

[MIT licence](LICENSE); vendored plugins keep their respective licences.
