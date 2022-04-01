# Kenny's dotfiles
This repo is a dumping ground for my personal config files--my "dotfiles".

If you're cruious, see https://wiki.archlinux.org/index.php/Dotfiles.

The directory structure here *should* replicate my home folder (`~/`).

This README also contains some notes about the setup of each program.

## Git
On Linux, `.gitconfig` goes in `~/`.

These commands can be used to generate my `.gitconfig`:
```bash
git config --global user.name "Kenny Kelley"
git config --global user.email "16879853+kenny-kelley@users.noreply.github.com"
git config --global core.editor vim
git config --global init.defaultBranch main
```

## Sublime Text
On Linux, `Preferences.sublime-settings` goes in `~/.config/sublime-text/Packages/User`.

I usually install the following packages via Package Control:
- TrailingSpaces
- INI
- Print to HTML
