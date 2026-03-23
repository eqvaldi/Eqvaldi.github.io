# Build Server

The Eqvaldi Debian build server (V2) is the automated pipeline used to produce all official image releases.

---

## Repository

[:material-github: Eqvaldi/Debian-build-server-V2](https://github.com/Eqvaldi/Debian-build-server-V2){ .md-button }

---

## Prerequisites

- A Debian or Ubuntu host machine (x86\_64 recommended)
- Docker or a compatible container runtime
- At least 20 GB of free disk space
- Git

---

## Building an image

```bash
git clone https://github.com/Eqvaldi/Debian-build-server-V2.git
cd Debian-build-server-V2
# Edit config.sh to select board, release line, and kernel flavour
./build.sh
```

The output image will be placed in the `output/` directory as a compressed `.img.xz` file.

---

## Selecting a kernel flavour

| Flavour | Description |
|---|---|
| `current` | Recommended LTS kernel |
| `edge` | Latest mainline kernel — more hardware support, less tested |
| `legacy` | Older LTS kernel — hardware-specific, use only if required |

!!! warning
    Legacy kernel builds were removed in V1.8. Do not use them on new installations.
