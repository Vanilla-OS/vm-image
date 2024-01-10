# Vanilla OS VM Image

Containerfile for building a Vanilla OS Desktop+VM image.

This image is based on top of [`vanillaos/desktop`](https://github.com/Vanilla-OS/desktop-image/pkgs/container/desktop) and offers the default Vanilla OS Desktop experience with GNOME and VM tools pre-installed.

## Build

```bash
sh prepare.sh
podman image build -t vanillaos/vm .
```
