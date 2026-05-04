# cave-builder

Builder container images.

## Images

| Image | Base | Tags |
|-------|------|------|
| `ghcr.io/atgreen/fedora-cave-builder` | Fedora | `43`, `latest` |

## What's included

- git, gcc, g++, make
- sbcl, ocicl
- golang
- autoconf, automake, libtool
- python3, pip
- zlib-devel

## Usage

```bash
podman pull ghcr.io/atgreen/fedora-cave-builder:latest
```
