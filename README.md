
```sh
# if chezmoi was installed
chezmoi init --apply https://github.com/kdrozd/dotfiles-linux.git

# if there is no chezmoi
sh -c "$(wget -qO- git.io/chezmoi)" -- init --apply https://github.com/kdrozd/dotfiles-linux.git
```
