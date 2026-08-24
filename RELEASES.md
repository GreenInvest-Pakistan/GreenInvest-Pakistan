# Windows releases and verification

## Install

1. Open the [latest release](https://github.com/GreenInvest-Pakistan/GreenInvest-Consumer/releases/latest).
2. Download `GreenInvest-Windows-x64.zip` and the SHA-256 checksum file.
3. Verify the archive.
4. Use Windows **Extract All** and run `GreenInvest.exe` from the extracted folder.

Do not run the executable directly from inside the ZIP. Keep the `_internal`
folder beside `GreenInvest.exe`; it contains the bundled Python, Qt WebEngine,
frontend, reference data, and calculation runtime.

## Verify with PowerShell or Windows Terminal

```powershell
Get-FileHash .\GreenInvest-Windows-x64.zip -Algorithm SHA256
```

Compare the printed hash with the release checksum file.

## Verify with Command Prompt

```bat
certutil -hashfile GreenInvest-Windows-x64.zip SHA256
```

The current public package is a portable 64-bit Windows preview. It is
self-contained but not code-signed. Download it only from the official release
page, and do not use a package whose checksum differs.

The ZIP includes `RELEASE-MANIFEST.txt` and a `THIRD-PARTY-LICENSES` directory
containing the exact bundled dependency manifest and redistribution notices.
