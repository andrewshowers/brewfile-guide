# Brewfile guide

One text file, the `Brewfile`, lists everything installed on my Mac. Keep it in git and a new machine matches the old one with a single command.

## Use it

```zsh
brew bundle --file Brewfile            # install everything listed
brew bundle check --file Brewfile      # report what's missing, installs nothing
brew bundle dump --file Brewfile --force   # overwrite the file from what's installed now
```

Install Homebrew first (see https://brew.sh).

## What's here

- `Brewfile`: my home Mac setup. Copy it and trim it to what you want.
- `HOMEBREW-GUIDE.md`: the conventions I follow, the everyday workflow, and notes on moving from an old machine.
