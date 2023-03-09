# alias

Collection of handy UNIX shell aliases.

## zsh

- `alias tree2="tree -L 2 ."`

Do not forget to `source .zshrc`!

## git

- `git config --global alias.hs "log --pretty='%C(yellow)%h %C(cyan)%cd %Cblue%aN%C(auto)%d %Creset%s' --date=relative --date-order"`
- `git config --global alias.c "rm -r --cached ."`