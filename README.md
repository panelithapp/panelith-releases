# Panelith downloads

This repository is **public downloads only**. It does not contain the source code. Panelith is developed in a separate repository.

Panelith draws live screens on USB sensor panels such as the Thermalright Trofeo Vision.

## Download

Download the newest installer, `Panelith-<version>-setup.exe`, from the [latest release](https://github.com/panelithapp/panelith-releases/releases/latest).

## Install

1. Run `Panelith-<version>-setup.exe` and follow the wizard.
2. Windows may warn that the publisher is unknown until Panelith has a certificate from a public authority. Choose **More info**, check the publisher is **Bharath Vadlamannati**, then **Run anyway**.
3. Check the download (optional). Each release lists SHA-256 hashes in `SHA256SUMS.txt`. In PowerShell:

   ```powershell
   Get-FileHash .\Panelith-<version>-setup.exe -Algorithm SHA256
   ```

Requires Windows 10 (1809) or Windows 11, 64-bit.

## Updates

Installed copies check this repository for new versions, verify them with the publisher's signature, and install them only when you choose. Nothing is installed without your say.

## Files in this repository

| File | What it is |
| --- | --- |
| `CHANGELOG.md` | What changed in each version. Each release's notes are the same text. |
| `LICENSE` | Panelith's license, PolyForm Noncommercial 1.0.0. Commercial use needs a separate license. |
| `NOTICE` | Copyright and attribution notice. |
| `THIRD-PARTY-LICENSES.md` | Every component Panelith ships, its license, and where its source is. |

## Support

Email **bharry29@gmail.com** with "Panelith" in the subject for bugs, questions, or security problems. Include the version and, for bugs, a log file from `%APPDATA%\Panelith\logs`.

Copyright (c) 2026 Bharath Vadlamannati.
