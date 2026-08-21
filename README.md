<div align="center">

![OmniVex Gaming Wrappers](assets/brand/banner-1600x500.svg)

# OmniVex Gaming Wrappers

### Choose the game. Omni handles the wrapper.

Four focused Windows compatibility installers with architecture-aware planning,
safe app-local deployment, automatic backup, and hash-checked rollback.

[![Version](https://img.shields.io/badge/version-1.0.0-8B5CF6?style=flat-square)](RELEASE-NOTES.md)
[![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-55C8FF?style=flat-square)](COMPATIBILITY.md)
[![Languages](https://img.shields.io/badge/UI%20languages-5-E7EBF2?style=flat-square&labelColor=303A48)](FEATURES.md)
[![Telemetry](https://img.shields.io/badge/telemetry-none-22D99A?style=flat-square)](PRIVACY.md)
[![Distribution](https://img.shields.io/badge/repository-docs%20only-99A3B1?style=flat-square&labelColor=303A48)](SOURCE-AVAILABILITY.md)

[Features](FEATURES.md) · [Compatibility](COMPATIBILITY.md) · [Quick start](QUICK-START.md) · [FAQ](FAQ.md) · [Deutsch](README-DE.md) · [Support](SUPPORT.md)

</div>

> [!IMPORTANT]
> This public repository contains documentation, graphics, and real UI
> screenshots only. It contains **no installer, executable, DLL, runtime
> payload, source code, or download release**.

## The family at a glance

![Four OmniVex products](assets/brand/products-1600x560.svg)

| Product | Best fit | Current runtime basis |
|---|---|---|
| **OmniDXVK** | Direct3D 8–11 games through Vulkan | DXVK 3.0.2 Omni · x86/x64 |
| **OmniDxWrapper** | Older 32-bit Windows games and legacy APIs | dxwrapper 1.7.8531.25 Omni · x86 |
| **OmniVoodoo2** | DirectDraw, early Direct3D, and 3Dfx Glide games | User-supplied official dgVoodoo2 2.87.3 package |
| **OmniVKD3D** | Experimental Direct3D 12 through Vulkan | vkd3d-proton 3.0.1 + OmniDXVK DXGI 3.0.2 · x86/x64 |

Compatibility always depends on the exact game, patch, GPU driver, mods, and
other injected software. A supported API is not a promise that every title will
work. OmniVKD3D is explicitly experimental on native Windows.

## A safer three-step flow

![OmniVex setup workflow](assets/brand/workflow-1600x420.svg)

1. **Target** — select the real game executable, not its launcher or shortcut.
2. **Compatibility** — review detected architecture, imported API, exact DLL
   names, required companions, warnings, and collisions.
3. **Deploy** — install the reviewed plan beside the game with backup enabled;
   roll back only the files matching the recorded installation.

## Consumer-first by design

![OmniVex core features](assets/brand/feature-grid-1600x520.svg)

- Automatic PE architecture inspection and graphics-import analysis.
- Exact proxy-DLL mapping with required companion expansion.
- Preview-before-write, protected-game warnings, and collision review.
- Per-game backup, bounded manifests, and hash-checked rollback.
- Five live UI languages: English, German, Spanish, French, and Romanian.
- Offline operation with no account, ads, telemetry, or background service.
- Privacy-redacted support packages and a controlled test-launch path.
- Precision Hybrid UI: flat graphite surfaces, compact technical labels,
  high-contrast states, and subtle preference-aware motion.

Engineering labs, benchmark panels, Wave centers, corpus tools, and maintainer
commands are deliberately excluded from the consumer interface.

## The actual installer experience

Every image below is a real capture of the current 1.0.0 installer candidate.

![All four OmniVex installers](assets/screenshots/omnivex-installer-collection.png)

| OmniDXVK | OmniDxWrapper |
|---|---|
| ![OmniDXVK installer](assets/screenshots/omni-dxvk-installer.png) | ![OmniDxWrapper installer](assets/screenshots/omni-dxwrapper-installer.png) |

| OmniVoodoo2 | OmniVKD3D Experimental |
|---|---|
| ![OmniVoodoo2 installer](assets/screenshots/omni-voodoo2-installer.png) | ![OmniVKD3D installer](assets/screenshots/omni-vkd3d-installer.png) |

## Donationware, without a paywall

OmniVex tools are free donationware: **no required payment and no ads**. If the
project saves you time or helps an older game run, optional support helps fund
testing, packaging, documentation, and support.

<div align="center">
  <a href="https://ko-fi.com/theomnigrid"><img src="assets/brand/btn-kofi-480x96.svg" width="360" alt="Support OmniVex on Ko-fi"></a>
  <a href="https://www.patreon.com/TheOmniGrid"><img src="assets/brand/btn-patreon-480x96.svg" width="360" alt="Support OmniVex on Patreon"></a>
</div>

Third-party runtimes keep their own licenses and rights. A donation does not
turn DXVK, dxwrapper, vkd3d-proton, or dgVoodoo2 into proprietary OmniVex
software. See [Legal & licenses](LEGAL.md), [Third-party notices](THIRD-PARTY-NOTICES.md),
and [Source availability](SOURCE-AVAILABILITY.md).

## Release status

Version **1.0.0** is a tested final candidate. The consumer-surface,
installation-flow, and documentation gates pass, but the delivery executables
are not yet Authenticode-signed. This repository is therefore a product
showcase and documentation home—not a public binary distribution channel.

- Consumer surface gate: **17/17 passed**
- Smart installation flow: **11/11 passed**
- Documentation maintenance gate: **4/4 passed**

Read the [release notes](RELEASE-NOTES.md) and [security policy](SECURITY.md) for
the current limits. For help, open an issue using the provided template or
email `omnivex@theomnigrid.biz`.

---

<div align="center">

**OmniVex · offline · private · reversible**

[TheOmniGrid on GitHub](https://github.com/TheOmniGrid) ·
[Ko-fi](https://ko-fi.com/theomnigrid) ·
[Patreon](https://www.patreon.com/TheOmniGrid)

<sub>Tuned for framerate, mixed for headroom, sharp to the pixel.<br>Donationware tools for gamers and audiophiles — audio, graphics, and a bit of privacy too.</sub>

</div>
