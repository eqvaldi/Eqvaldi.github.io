# Building Overview

Eqvaldi provides everything you need to build your own images from source. There are two main paths: the **build server** (automated, server-side) and **install scripts** (post-install configuration on a running system).

---

## Quick start

```bash
git clone https://github.com/Eqvaldi/build.git
cd build
./compile.sh
```

See the build server repository for full documentation on compile flags, supported boards, and kernel selection.

---

## Build paths

<div class="grid cards" markdown>

-   :material-server:{ .lg .middle } **Build Server**

    ---

    The primary build system. Produces `.img.xz` images for all supported platforms.

    [:octicons-arrow-right-24: Build Server guide](build-server.md)

-   :material-script:{ .lg .middle } **Install Scripts**

    ---

    Post-install scripts for configuring a fresh Debian system with the Eqvaldi package set.

    [:octicons-arrow-right-24: Install Scripts guide](install-scripts.md)

</div>

---

## Source repositories

| Repository | Description |
|---|---|
| [Eqvaldi/build](https://github.com/Eqvaldi/build) | Main build environment (images) |
| [Eqvaldi/Debian-build-server-V2](https://github.com/Eqvaldi/Debian-build-server-V2) | Automated build server |
| [Eqvaldi/install-scripts](https://github.com/Eqvaldi/install-scripts) | Debian post-install scripts |
| [Eqvaldi/releases](https://github.com/Eqvaldi/releases) | Release artifacts |
