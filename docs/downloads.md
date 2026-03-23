# Downloads

Three release channels are available. Choose the one that fits your needs.

---

## Release channels

=== "Stable"
    Production-ready builds. Recommended for daily use.

    [:material-download: Download Stable](https://github.com/Eqvaldi/releases/releases){ .md-button .md-button--primary }

=== "Edge"
    Builds with newer kernels, but less tested. Good for hardware that requires recent drivers.

    [:material-download: Download Edge](https://github.com/Eqvaldi/releases/releases){ .md-button }

=== "Rolling"
    Latest development snapshots built from the **dev** branch. May be unstable.

    [:material-download: Download Rolling](https://github.com/Eqvaldi/build/releases){ .md-button }

---

## Supported platforms

| Platform | V2-LTS | V3-LTS | V4-dev |
|---|:---:|:---:|:---:|
| x86\_64 | :material-check: | :material-check: | :material-check: |
| ARM64 | :material-check: | :material-check: | :material-check: |
| ARMHF | :material-check: | :material-check: | :material-check: |
| Jetson Nano | :material-close: | :material-check: | EOL |

---

## Verifying downloads

After downloading, verify your image before flashing.

```bash
sha256sum Eqvaldi-*.img.xz
```

Compare the output against the checksum file published alongside the release on GitHub.
