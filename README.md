# Kenny's dotfiles
The ArchWiki has a nice article about dotfiles:
- https://wiki.archlinux.org/title/Dotfiles

The structure here *should* replicate that of my home folder (`~/`).

This README also contains some notes about the setup of some programs.

## Git
These commands can be used to generate my `~/.gitconfig` from scratch:
```bash
git config --global user.name "Kenny Kelley"
git config --global user.email "16879853+kenny-kelley@users.noreply.github.com"
git config --global core.editor vim
git config --global init.defaultBranch main
```

## Sublime Text
I usually install the following packages via Package Control:
- INI
- Print to HTML
- TrailingSpaces
