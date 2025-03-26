This is a GNU stow dotfiles repo. In order to bootstrap clone this repo into `$HOME/,config/dotfiles`, change into that dir and run

```bash
stow -t $HOME stow
```

Afterwards stow is configured to read stow packages from `$HOME/.config/dotfiles` and to use `$HOME` as target dir.
