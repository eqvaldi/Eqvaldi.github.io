# Install Scripts

Post-install scripts for configuring a fresh Debian system with the Eqvaldi package set and customizations.

---

## Repository

[:material-github: Eqvaldi/install-scripts](https://github.com/Eqvaldi/install-scripts){ .md-button }

---

## Usage

Clone the repository onto a freshly installed Debian system and run the appropriate script for your target:

```bash
git clone https://github.com/Eqvaldi/install-scripts.git
cd install-scripts
bash install.sh
```

!!! tip
    Run the install scripts as root or with `sudo`. Review each script before executing to understand what packages and configurations will be applied.

---

## What the scripts do

- Install the Eqvaldi package set (desktop, multimedia, utilities)
- Apply system configuration defaults
- Set up the Cinnamon or MATE desktop environment
- Configure kernel and firmware packages appropriate for your hardware
