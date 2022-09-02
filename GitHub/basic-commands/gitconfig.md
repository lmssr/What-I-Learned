# Git Config

You can use the Git configuration file to customize how Git works.
To open the .gitconfig file, you have type 

```sh
git config --global -e
```

You can also use direct commands to change some parameters in your config file.

For exemple:

```sh
git config --global core.editor "code --wait"
```
- This configuration tells Git that for operations like commits and tags, I want to use my VSCode editor.

```sh
git config --global fetch.prune true
```
- Pruning during fetch is a cleanup method that deletes outdated remote references in your .git directory when you do a git fetch --prune.

- With this, pruning will occur whenever you do a git fetch.