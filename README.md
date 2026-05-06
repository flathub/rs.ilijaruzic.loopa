[![Flathub](https://img.shields.io/flathub/v/rs.ilijaruzic.loopa)](https://flathub.org/apps/rs.ilijaruzic.loopa)
[![Packages](https://img.shields.io/github/v/tag/ilijaruzic/loopa-packages?label=loopa-packages)](https://github.com/ilijaruzic/loopa-packages/releases)
[![License](https://img.shields.io/badge/license-Proprietary-red)](https://github.com/ilijaruzic/loopa-packages/blob/main/LICENSE)

This repository contains the flatpak packaging manifest for Loopa, a cross-platform desktop application developed by Ilija Ruzic.

## Distribution

Loopa is proprietary software.

Redistribution of unmodified copies is permitted in accordance with the
End-User License Agreement.

## Building

```bash
flatpak-builder --user --install --force-clean build-dir rs.ilijaruzic.loopa.yml
flatpak run rs.ilijaruzic.loopa
```
