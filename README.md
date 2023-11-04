# Vanilla OS Cosmic Image

Containerfile for building a Cosmic Flavor of the Vanilla OS Desktop image.

This image is based on top of [`vanillaos/desktop-image`](https://github.com/Vanilla-OS/desktop-image) and offers a 
Cosmic Flavor of the Vanilla OS Desktop experience.

## Build

```bash
sh prepare.sh
podman image build -t vanillaos/cosmic-desktop-image .
```
