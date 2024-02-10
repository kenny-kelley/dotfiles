# Using `stow`
I use `stow` to manage my dotfiles, so the structure here replicates that of `~/`.

If you want to put new symlinks into your home folder, run this:
```bash
stow -t ~/ .
```

There are also cases where you might want to import (or "adopt") the files in your home folder over top of the things here:
```bash
stow -t ~/ --adopt .
```

Be careful. This stuff can be messy to clean up if it goes wrong. See `man stow`.
