After cloning the folder, make sure that something like

```bash
if [ -f ~/THIS REPO/.bash_aliases ]; then
    . ~/THIS REPO/.bash_aliases
fi
```

is included in your .bashrc to check for, and load the aliases.
