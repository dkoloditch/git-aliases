# git-aliases
Git terminal / command-line shortcuts

Just copy and paste one of the following lines in your terminal.

.bashrc
```
(cd $HOME && wget https://raw.githubusercontent.com/dkoloditch/git-aliases/master/.git_aliases) && (echo "" >> $HOME/.bashrc && echo "source $HOME/.git_aliases" >> $HOME/.bashrc) && source $HOME/.bashrc
```

.bash_profile (e.g. OS X)
```
(cd $HOME && wget https://raw.githubusercontent.com/dkoloditch/git-aliases/master/.git_aliases) && (echo "" >> $HOME/.bash_prompt && echo "source $HOME/.git_aliases" >> $HOME/.bash_prompt) && source $HOME/.bash_prompt
```

## Uninstall
1. ```rm $HOME/.git_aliases```
2. Open $HOME/.bashrc or $HOME/.bash_profile and remove the line "source $HOME/.git_aliases"

Enjoy.
