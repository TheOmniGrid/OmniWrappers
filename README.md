<p align="center">
  <img src="assets/brand/banner-animated.gif" alt="OmniWrappers — choose the game, Omni handles the wrapper" width="100%">
</p>

<h1 align="center">OmniWrappers</h1>
<p align="center"><b>Choose the game. Omni handles the wrapper — four focused Windows compatibility installers with architecture-aware planning, safe app-local deployment, automatic backup, and hash-checked rollback.</b></p>
<p align="center">Part of the <a href="#the-omnivex-suite">OmniVex</a> suite.</p>

<p align="center">
  <a href="https://www.patreon.com/TheOmniGrid"><img alt="Get it on Patreon" src="https://img.shields.io/badge/Get%20it%20on-Patreon-FF424D?style=for-the-badge&logo=patreon&logoColor=white"></a>
  &nbsp;
  <a href="https://ko-fi.com/theomnigrid"><img alt="Get it on Ko-fi" src="https://img.shields.io/badge/Get%20it%20on-Ko--fi-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white"></a>
</p>

<p align="center">
  <a href="CHANGELOG.md"><img alt="Version" src="https://img.shields.io/badge/version-1.0.0-8B5CF6?style=flat-square"></a>
  <a href="COMPATIBILITY.md"><img alt="Platform" src="https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-55C8FF?style=flat-square"></a>
  <a href="FEATURES.md"><img alt="Languages" src="https://img.shields.io/badge/languages-EN%20%C2%B7%20DE%20%C2%B7%20ES%20%C2%B7%20FR%20%C2%B7%20RO-8B5CF6?style=flat-square"></a>
  <a href="PRIVACY.md"><img alt="Telemetry" src="https://img.shields.io/badge/telemetry-none-22D99A?style=flat-square"></a>
  <a href="SOURCE-AVAILABILITY.md"><img alt="Distribution" src="https://img.shields.io/badge/distribution-docs%20only-99A3B1?style=flat-square&labelColor=303A48"></a>
</p>

<!-- Quick navigation. These chips jump to sections on this page or to the
     document they name. Keep each target synchronized if a heading changes. -->
<p align="center">
  <a href="#get-omniwrappers"><img alt="Get OmniWrappers" src="https://img.shields.io/badge/Get%20OmniWrappers-8B5CF6?style=for-the-badge"></a>
  <a href="#consumer-first-by-design"><img alt="Features" src="https://img.shields.io/badge/Features-232B36?style=for-the-badge"></a>
  <a href="#the-family-at-a-glance"><img alt="Products" src="https://img.shields.io/badge/Products-232B36?style=for-the-badge"></a>
  <a href="#a-safer-three-step-flow"><img alt="Workflow" src="https://img.shields.io/badge/Workflow-232B36?style=for-the-badge"></a>
  <a href="#the-actual-installer-experience"><img alt="Screenshots" src="https://img.shields.io/badge/Screenshots-232B36?style=for-the-badge"></a>
  <a href="PRIVACY.md"><img alt="Privacy" src="https://img.shields.io/badge/Privacy-232B36?style=for-the-badge"></a>
  <a href="COMPATIBILITY.md"><img alt="Compatibility" src="https://img.shields.io/badge/Compatibility-232B36?style=for-the-badge"></a>
  <a href="INSTALLATION.md"><img alt="Installation" src="https://img.shields.io/badge/Installation-232B36?style=for-the-badge"></a>
  <a href="FAQ.md"><img alt="FAQ" src="https://img.shields.io/badge/FAQ-232B36?style=for-the-badge"></a>
  <a href="SUPPORT.md"><img alt="Support" src="https://img.shields.io/badge/Support-232B36?style=for-the-badge"></a>
  <a href="CHANGELOG.md"><img alt="Changelog" src="https://img.shields.io/badge/Changelog-232B36?style=for-the-badge"></a>
</p>

> [!IMPORTANT]
> **Documentation-only repository.** This public repository contains documentation, graphics, and real UI
> screenshots only. It contains **no installer, executable, DLL, runtime
> payload, source code, or download release**.

## Consumer-first by design

![OmniWrappers core features](assets/brand/feature-grid-1600x520.svg)

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

## The family at a glance

![Four OmniWrappers products](assets/brand/products-1600x560.svg)

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

![OmniWrappers setup workflow](assets/brand/workflow-1600x420.svg)

1. **Target** — select the real game executable, not its launcher or shortcut.
2. **Compatibility** — review detected architecture, imported API, exact DLL
   names, required companions, warnings, and collisions.
3. **Deploy** — install the reviewed plan beside the game with backup enabled;
   roll back only the files matching the recorded installation.

## The actual installer experience

Every image below is a real capture of the current 1.0.0 installer candidate.

![All four OmniWrappers installers](assets/screenshots/omnivex-installer-collection.png)

| OmniDXVK | OmniDxWrapper |
|---|---|
| ![OmniDXVK installer](assets/screenshots/omni-dxvk-installer.png) | ![OmniDxWrapper installer](assets/screenshots/omni-dxwrapper-installer.png) |

| OmniVoodoo2 | OmniVKD3D Experimental |
|---|---|
| ![OmniVoodoo2 installer](assets/screenshots/omni-voodoo2-installer.png) | ![OmniVKD3D installer](assets/screenshots/omni-vkd3d-installer.png) |

## Get OmniWrappers

OmniWrappers is free donationware: **no required payment and no ads**. If the
project saves you time or helps an older game run, optional support helps fund
testing, packaging, documentation, and support.

<div align="center">
  <a href="https://www.patreon.com/TheOmniGrid"><img src="assets/brand/support-patreon.svg" height="64" alt="Support OmniWrappers on Patreon"></a>
  <a href="https://ko-fi.com/theomnigrid"><img src="assets/brand/support-kofi.svg" height="64" alt="Support OmniWrappers on Ko-fi"></a>
</div>

Third-party runtimes keep their own licenses and rights. A donation does not
turn DXVK, dxwrapper, vkd3d-proton, or dgVoodoo2 into proprietary OmniWrappers
software. See [License](LICENSE.md), [Third-party notices](THIRD-PARTY-NOTICES.md),
and [Source availability](SOURCE-AVAILABILITY.md).

## Documentation

| | |
|---|---|
| [Installation](INSTALLATION.md) | Choose a wrapper and follow the guarded installation flow |
| [Features](FEATURES.md) | Product capabilities and safety boundaries |
| [Compatibility](COMPATIBILITY.md) | Supported games, renderers and known limits |
| [Privacy](PRIVACY.md) | Local data, network access and telemetry boundaries |
| [FAQ](FAQ.md) | Common wrapper, install and rollback questions |
| [Support](SUPPORT.md) | Useful reports, privacy redaction and contact routes |
| [Security](SECURITY.md) | Private vulnerability reporting |
| [Contributing](CONTRIBUTING.md) | Documentation and reproducible-report scope |
| [Changelog](CHANGELOG.md) | Release history and current status |
| [Licence](LICENSE.md) | OmniVex material and third-party licence boundaries |
| [Third-party notices](THIRD-PARTY-NOTICES.md) | Upstream runtimes and licences |
| [Source availability](SOURCE-AVAILABILITY.md) | Source obligations for distributed runtimes |

## Current status

Version **1.0.0** is a tested final candidate. The consumer-surface,
installation-flow, and documentation gates pass, but the delivery executables
are not yet Authenticode-signed. This repository is therefore a product
showcase and documentation home—not a public binary distribution channel.

- Consumer surface gate: **17/17 passed**
- Smart installation flow: **11/11 passed**
- Documentation maintenance gate: **4/4 passed**

Read the [changelog](CHANGELOG.md) and [security policy](SECURITY.md) for
the current limits. For help, open an issue using the provided template or
email `omnivex@theomnigrid.biz`.

## The OmniVex suite

OmniWrappers is one of a family of tools sharing a design language and a philosophy —
modern, fast, no telemetry:

**OmniTheme** · **OmniBlock** · **OmniCleaner** · **OmniAPO** · **OmniEQ** · **OmniPlay** · **OmniScale** · **OmniShade** · **OmniVisuals** · **OmniGPU** · **OmniWrappers**

<sub>**OmniWrappers** is four Direct3D compatibility installers — OmniDXVK, OmniDxWrapper, OmniVKD3D and OmniVoodoo2.</sub>

<sub>Tuned for framerate, mixed for headroom, sharp to the pixel. Donationware
tools for gamers and audiophiles — audio, graphics, and a bit of privacy too.</sub>

More at [github.com/TheOmniGrid](https://github.com/TheOmniGrid).

---

## Credit

OmniWrappers deploys other people's runtimes. The installers, their UI, the presentation
assets and the deployment logic are OmniVex's; the wrappers themselves are not, and the
projects behind them are the reason any of this works:

- **[DXVK](https://github.com/doitsujin/dxvk)** — zlib/libpng licence. Altered versions
  must be marked as such and the origin must not be misrepresented; the OmniDXVK
  modifications are marked accordingly.
- **[dxwrapper](https://github.com/elishacloud/dxwrapper)** — zlib-style licence; its
  included MemoryModule portions are MPL 2.0.
- **[vkd3d-proton](https://github.com/HansKristian-Work/vkd3d-proton)** — LGPL 2.1.
- **[dgVoodoo2](http://dege.freeweb.hu/)** by **Dege** — **not embedded**. You supply the
  official, hash-pinned 2.87.3 package yourself, under the author's own terms.

OmniWrappers is not affiliated with Microsoft, Khronos, Valve, 3dfx or the upstream wrapper
authors unless explicitly stated.

Full detail in [License](LICENSE.md) · [Third-party notices](THIRD-PARTY-NOTICES.md) ·
[Source availability](SOURCE-AVAILABILITY.md)

---

## Contact

This is a documentation-only public repository. Documentation corrections, reproducible
compatibility reports, accessibility feedback and translations are all welcome — open an
issue using the provided template. Source code, installer binaries, runtime DLLs and
release evidence are not accepted here; see [CONTRIBUTING.md](CONTRIBUTING.md).

**omnivex@theomnigrid.biz**

---

<div align="center">

**OmniWrappers · offline · private · reversible**

[TheOmniGrid on GitHub](https://github.com/TheOmniGrid) ·
[Ko-fi](https://ko-fi.com/theomnigrid) ·
[Patreon](https://www.patreon.com/TheOmniGrid)

Copyright © 2026 OmniVex · Documentation-only repository<br>
<sub>DXVK, dxwrapper, vkd3d-proton and dgVoodoo2 are the work of their respective authors and remain under their own licences. Direct3D and Windows are trademarks of Microsoft Corporation.</sub>

</div>
