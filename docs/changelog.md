# Changelog

Full release history across all release lines.

## V4-LTS

Release4.0 (V4-LTS)

- Replace spek with sox.
- Add new image variant: minimal (no Desktop Env.)
- Add new image variant: KDE
- Bump Armbian to 26.02.0
- Bump Debian to 13.3
- Bunp linux kernels to 2026.2.4.
- Replace `neofetch` with `hyfech`.
- Add pakages :`libsdl2-net-dev` `spek` `orchis-gtk-theme` `libsndfile1-dev`.
- Remove Jetson Nano and Debian 12 builds.
- Remove pakages :`qtbase5-dev` `qtbase5-private-dev` `qtbase5-dev-tools` `qttools5-dev`
- LXQT replaces LXDE.

## V3-LTS

Release3.6 (V3-LTS)

- Bump Armbian to 25.11
- Bump Debian to 12.12
- Bunp linux kernels to 2025.11.23.
- Add pakages :`eject` `libzip-dev` `zipcmp` `zipmerge` `ziptool` `libsdl2-mixer-dev`
- Add numix icon theme
- Remove Jetson Nano builds
- Remove pakages :`qtbase5-dev` `qtbase5-private-dev` `qtbase5-dev-tools` `qttools5-dev`

### Release 3.5.063024-dev

- Bump Armbian to 24.8
- Bump Debian to 12.6
- Bump Linux kernels to 2024.6.30
- Add packages: `eject`, `libzip-dev`, `zipcmp`, `zipmerge`, `ziptool`, `libsdl2-mixer-dev`
- Add Numix icon theme

### Release 3.3.100623

- Bump Armbian to 23.11
- Bump Debian to 12.2
- Add packages: `libsdl2-net-dev`, `spek`

### Release 3.2.080623

- Bump Armbian to 23.08
- Add back Jetson Nano builds
- Bump Debian to 12.1
- Add packages: `alsa-firmware-loaders`, `cifs-utils`, `vainfo`, `vdpauinfo`, `glmark2`, `pciutils`, `firmware-nvidia-gsp` (x86 only)
- Build Debian 13 for testing with EDGE kernel

### Release 3.0.053023

- Bump Armbian to 23.05
- Add packages: `bash-completion`, `alsa-utils`, `apt-utils`, `sudo`, `alsa-firmware-loaders`, `cifs-utils`
- Move to Bookworm (Debian 12)
- Bump Linux kernel versions: 6.1.xx, 5.4.242, EDGE 6.3.x (Current)

---

## V2-LTS

### Release 2.8.063024-dev

- Bump Armbian to 24.8
- Bump Linux kernels to 2024.6.30

### Release 2.7.100623

- Bump Armbian to 23.11
- Bump Debian to 11.8
- Add packages: `libsdl2-net-dev`

### Release 2.6.080623

- Bump Armbian to 23.08

### Release 2.5.053023

- Bump Armbian to 23.05
- Bump Debian to 11.7
- Add packages: `bash-completion`, `alsa-utils`, `apt-utils`, `sudo`, `alsa-firmware-loaders`, `cifs-utils`
- Bump Linux kernel versions: 6.1.xx, 5.4.242, EDGE 6.3.x (Current)

### Release 2.1.031423

- Move to minimal from standard Debian
- Remove Jetson Nano builds
- Bump Armbian to 23.02
- Bump Debian to 11.6
- Add `firmware-sof-signed` (x86 only)
- Add `openarena` (later removed)

---

## V1-LTS *(EOL)*

!!! warning "End of Life"
    V1-LTS no longer receives updates or security fixes.

### Release 1.8

- Add packages: `git`, `nasm`, `libgl1-mesa-dev`, `libsdl2-dev`, `libflac-dev`, `libvpx-dev`, `libgtk2.0-dev`, `freepats`, `ninja-build`, `qtbase5-dev`, `qtbase5-private-dev`, `qtbase5-dev-tools`, `qttools5-dev`
- Bump Armbian to 22.11.0
- Bump Debian to 11.5
- Bump Linux kernel versions: 5.15.74, 5.19.16, 5.10.147, 5.4.218 (Current)
- Remove legacy kernel builds
- Add more SBCs to Cinnamon
- Revert to Chromium as default web browser

### Release 1.1

- Remove XFCE4 power-manager and power-manager-plugins (MATE Desktop)
- Add Cinnamon DE
- Add MATE power manager (MATE Desktop)
- Bump Linux kernel versions: 5.15.48, 5.17.15, 5.4.199, 5.10.123 (Current)
- Bump Debian to 11.4

### Release 1.0

- Initial release
