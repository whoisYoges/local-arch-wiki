# local-arch-wiki

An offline version of [arch linux wiki](https://wiki.archlinux.org/) inspired from [dm-wiki](https://gitlab.com/dwt1/dmscripts/-/blob/master/scripts/dm-wiki).

# Dependencies

- [arch-wiki-docs](https://archlinux.org/packages/community/any/arch-wiki-docs/)
- [dmenu](https://tools.suckless.org/dmenu/) or [rofi](https://github.com/davatorium/rofi)
- a web browser
- find
- cut 
- sed
- sort

### Optional Dependencies

- xdg-utils
- notify-send

# Installation and Usage

## In arch based distributions.

Use your favourite aur helper. Eg: yay
```
yay -S local-arch-wiki
```
## From Source

1. Install all the required dependencies according to the distribution you use.
2. Install [local-arch-wiki](local-arch-wiki) in your system.

```
curl -O "https://raw.githubusercontent.com/whoisYoges/local-arch-wiki/master/local-arch-wiki"
chmod +x local-arch-wiki
sudo mv local-arch-wiki /usr/local/bin/
```

# Uninstallation
1. Remove all the [dependencies](#dependencies) that you don't require (Be careful other packages may need these dependencies).
2. Uninstall [local-arch-wiki](local-arch-wiki) from your system.

```
sudo rm /usr/local/bin/local-arch-wiki
```
