# Security policy

Report suspected installer vulnerabilities privately to `omnivex@theomnigrid.biz`.
Include product/version, reproduction steps and the SHA-256 of the installer.
Do not publish an exploit before a fix or mitigation is available.

## Verify a download

If an official download is made available, compare its SHA-256 with the value
published alongside that exact build:

```powershell
Get-FileHash -Algorithm SHA256 .\OmniDXVK-Installer.exe
```

The 1.0.0 final candidate is not Authenticode-signed and is not distributed
through this repository. Production publication should use a timestamped
code-signing certificate; until then Windows SmartScreen may show an
unknown-publisher warning.
