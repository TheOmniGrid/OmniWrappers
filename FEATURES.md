# Feature list

## Shared across all four installers

### Automatic setup

- Reads the selected PE executable and detects x86, x64, ARM64 or ARM64EC.
- Refuses unsupported architecture combinations instead of copying a bad DLL.
- Maps imported graphics APIs to exact Windows proxy filenames.
- Expands required companion DLLs automatically.
- Shows the complete deployment plan before any write.

### Safe per-game installation

- Writes only beside the chosen game executable.
- Resolves the real executable and directory through Windows handles, including
  junction and symbolic-link aliases, before applying path policy.
- Detects existing wrappers and requires a reviewed decision on collisions.
- Backs up replaced files by default.
- Records installed hashes and restores only the matching installation.
- Bounds rollback manifests and streams backup restoration with fixed memory.
- Provides a reversible rollback flow without a global Windows uninstall.

### Friendly consumer experience

- Consumer-only interface without engineering or benchmark panels.
- Five live UI languages: English, Deutsch, Español, Français and Română.
- Plain-language hover help and UI Automation help text.
- Game discovery, launcher-to-real-EXE detection and drag/drop path entry.
- Game check, controlled test launch and privacy-redacted support package.
- Precision Hybrid styling with flat graphite surfaces, compact technical
  labels, subtle preference-aware motion, and high-contrast support.

## OmniDXVK

- Direct3D 8, 9, 10 Core and 11 plus DXGI mappings.
- Automatic D3D8→D3D9 and D3D10/11→DXGI companion planning.
- x86 and x64 architecture-matched DXVK payloads.

## OmniDxWrapper

- 22 legacy proxy names covering graphics, input, audio, media and system APIs.
- Truthful x86-only gate matching the current runtime.
- One shared core with generated per-game INI settings.
- Optional reviewed chain to one existing compatible x86 proxy.

## OmniVoodoo2

- DirectDraw / Direct3D 1–7, Direct3D 8/9 and Glide 1/2/3 mappings.
- Standard and Napalm Glide 3 choices with collision prevention.
- Pinned SHA-256 validation for the user's official dgVoodoo2 2.87.3 ZIP.
- Primary-package-only x86 path; Dev64 companion only for x64/ARM64.
- Automatic package lookup beside the installer and in Downloads.

## OmniVKD3D

- Experimental D3D12 plan containing `d3d12.dll`, `d3d12core.dll` and `dxgi.dll`.
- Enforces the inseparable architecture-matched runtime set.
- Preserves upstream provenance and exact runtime identity.

## Release integrity

- Build-consumed payload lock covers all 22 staged runtime/config resources by
  path, bytes, SHA-256, PE machine, origin, and license.
- Signed-update parsing consumes the exact byte snapshot verified by CMS.
- Authenticode validation requests whole-chain revocation checking.
- Runtime smoke probes refuse elevated execution and restrict Windows DLL search.

## Deliberately not included

- Anti-cheat bypasses, process hiding or protected-game patching.
- Global DLL installation into Windows system directories.
- Permanent background services, telemetry or online accounts.
- Public developer labs, Wave centers, benchmark/corpus tools or maintainer CLI.
- A promise that every game or mod combination will work.
