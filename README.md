# root-stow

The configuration file tree for linux root filesystem.
With stow, the tree is mapping to root fs via symbolic link.

## Apply

```
sudo stow -v root -t /
```

## Undo

```
sudo stow -D -v root -t /
```
