# Vanilla OS VM Image

Containerfile for building a Vanilla OS Desktop+VM image.

This image is based on top of [`vanillaos/desktop`](https://github.com/Vanilla-OS/desktop-image/pkgs/container/desktop) and offers the default Vanilla OS Desktop experience with GNOME and VM tools pre-installed.

## Build

> [!NOTE]
> The fsguard compiled plugin `.so` file should be downloaded from the [latest release](https://github.com/Vanilla-OS/vib-fsguard/releases/latest) and be placed under a `plugins` directory beside the `recipe.yml` file.

```bash
vib build recipe.yml
podman image build -t vanillaos/vm .
```
