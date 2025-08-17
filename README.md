# Ren'Paste

_Shell utility to quickly copy Ren'Py saves to desired folder, by launching like a regular app_

## Installation

Linux only for now. If you are not using Bottles flatpak version or your Bottle path is different than the default, make sure to edit `ROOT_SRC_DIR` variable in `renpaste`.

### Requirements

Make sure you have `curl`, `inotify-tools` and `findutils` installed. Package name can differ based on your distro.

### Automatic (Recommended)

```sh
bash <(curl -s https://raw.githubusercontent.com/aintnodev/renpaste/main/setup) -i
```

### Manual

```sh
git clone https://github.com/aintnodev/renpaste.git
cd renpaste

mkdir -p $HOME/.local/bin
cp renpaste $HOME/.local/bin

mkdir -p $HOME/.local/share/applications
cp renpaste.desktop $HOME/.local/share/applications

mkdir -p $HOME/.local/share/icons/hicolor/48x48/apps
cp renpaste.png $HOME/.local/share/icons/hicolor/48x48/apps
```

### Uninstall

```sh
bash <(curl -s https://raw.githubusercontent.com/aintnodev/renpaste/main/setup) -u
```
