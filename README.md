# IntuneWin

Microsoft Intune Win32 application packages and documentation created by ESB s.r.o https://esb.sk/ .

## Packages

The `.intunewin` and `Source Code` files are published in GitHub Releases.

## Applications

- Autogram          -> https://github.com/ESB-Git/IntuneWin/releases/tag/autogram-v2.7.4
- eID Klient        -> https://github.com/ESB-Git/IntuneWin/releases/tag/eid-klient-v5.3.0
- DISIG Web Signer  -> https://github.com/ESB-Git/IntuneWin/releases/tag/disig-web-signer-v2.5.5
- D.Suite 2         -> https://github.com/ESB-Git/IntuneWin/releases/tag/dsuite-eidas-v2.0.7

## How to import to Intune

1. Download the required `.intunewin` package from Releases.
2. Go to Microsoft Intune admin center.
3. Apps > Windows > Add.
4. Select Windows app (Win32).
5. Upload the `.intunewin` file.
6. Configure app information based on the provided manifest.
7. Configure install/uninstall commands.
8. Configure detection rules.
9. Assign to a test group first.

## Disclaimer

This repository is an open-source community-maintained collection of Microsoft Intune Win32 deployment documentation, manifests, detection scripts, and packaging guidance.

The deployment templates, documentation, and scripts provided in this repository are intended to help IT administrators package and deploy applications through Microsoft Intune.

This repository is not an official distribution channel for the listed applications and is not affiliated with, endorsed by, or maintained by the original software vendors, unless explicitly stated otherwise.

All product names, trademarks, and software belong to their respective owners.

The maintainers of this repository provide the content "as is", without warranty of any kind. Always test packages in a pilot group before deploying them to production devices.
