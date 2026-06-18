# IntuneWin

Microsoft Intune Win32 application packages and documentation.

## Packages

The `.intunewin` files are published in GitHub Releases.

## Applications

- Autogram
- eID Klient -> https://github.com/ESB-Git/IntuneWin/releases/tag/eid-klient-v5.3.0
- DISIG Web Signer
- D.Suite 2

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
