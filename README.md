# local-arch-wiki

A convenient wrapper for arch-wiki-docs, enabling effortless searching and access to the offline Arch Wiki.

# Index
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Configuration](#configuration)
- [Uninstallation](#uninstallation)

# Dependencies

- [arch-wiki-docs](https://archlinux.org/packages/community/any/arch-wiki-docs/)
- A menu such as [dmenu](https://tools.suckless.org/dmenu/), [rofi](https://github.com/davatorium/rofi), or [tofi](https://github.com/philj56/tofi). Configure Accordingly in the `config` file.
- A web browser. Configure Accordingly in the `config` file.
- find
- cut
- sed
- sort

### Optional Dependencies

- libnotify (For notification support.)

# Installation

## From Source

1. Install all the required [dependencies](#dependencies) according to the distribution you use.
2. Install [local-arch-wiki](local-arch-wiki) in your system.

```
curl -LOS "https://raw.githubusercontent.com/whoisYoges/local-arch-wiki/master/local-arch-wiki"
chmod +x local-arch-wiki
sudo mv local-arch-wiki /usr/local/bin/
```

# Configuration
local-arch-wiki will by default create a config file at `$HOME/.config/local-arch-wiki/config` on first run. This file contains options to configure your wiki directory, browser and menu. Firefox is used as the web browser and tofi is used as menu by default.

# Uninstallation
1. Remove the installed [dependencies](#dependencies). (Be careful other packages may need these dependencies).
2. Uninstall [local-arch-wiki](local-arch-wiki) from your system.

```
sudo rm /usr/local/bin/local-arch-wiki
```
