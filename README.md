# root-stow

The configuration file tree for linux root filesystem.
With stow, the tree is mapping to root fs via symbolic link.

## Intialize

```
$ git clone https://github.com/onokatio/root-stow
$ sudo mv ./root-stow /
$ cd /root-stow
$ sudo chown -R root:root ./root
```

**Run chown for security.**

## Apply

```
sudo stow -v root -t /
```

## Undo

```
sudo stow -D -v root -t /
```
