# local-arch-wiki
An offline version of [arch linux wiki](https://wiki.archlinux.org/) inspired from [dm-wiki](https://gitlab.com/dwt1/dmscripts/-/blob/master/scripts/dm-wiki).

# Dependencies
- [arch-wiki-docs](https://archlinux.org/packages/community/any/arch-wiki-docs/)
- [dmenu](https://tools.suckless.org/dmenu/) (or you could use rofi as well change accordingly in [local-arch-wiki](local-arch-wiki).)
- a web browser (firefox as default; change to your favourite one in [local-arch-wiki](local-arch-wiki).)
- cut 
- sed
- sort

# Installation and Usage
1. Install all the required dependencies according to the distribution you use.
2. Install [local-arch-wiki](local-arch-wiki) in your system.
```
curl "https://raw.githubusercontent.com/whoisYoges/local-arch-wiki/master/local-arch-wiki" > local-arch-wiki
chmod +x local-arch-wiki
sudo mv local-arch-wiki /usr/local/bin/
```

# Uninstallation
1. Remove all the [dependencies](#dependencies) that you don't require (Be careful other packages may need these dependencies).
2. Uninstall [local-arch-wiki](local-arch-wiki) from your system.
```
sudo rm /usr/local/bin/local-arch-wiki
```
