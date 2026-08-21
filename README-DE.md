<div align="center">

![OmniWrappers](assets/brand/banner-1600x500.svg)

# OmniWrappers 1.0.0

### Spiel auswählen. Omni kümmert sich um den Wrapper.

[English](README.md) · [Funktionen](FEATURES.md) · [Kompatibilität](COMPATIBILITY.md) · [Schnellstart](QUICK-START.md) · [Support](SUPPORT.md)

</div>

> [!IMPORTANT]
> Dieses öffentliche Repository enthält ausschließlich Dokumentation, Grafiken
> und echte UI-Screenshots. Es enthält **keine Installer, EXE-/DLL-Dateien,
> Runtime-Payloads, Quelltexte oder Download-Releases**.

OmniWrappers besteht aus vier übersichtlichen Windows-Installern für Spiele. Sie
analysieren die echte Spiel-EXE, erkennen deren Architektur und importierte
Grafik-APIs, wählen gültige DLL-Namen und zeigen jede geplante Datei vor dem
Schreiben an.

![Vier OmniWrappers-Produkte](assets/brand/products-1600x560.svg)

- **OmniDXVK:** Direct3D 8–11 über Vulkan, x86/x64.
- **OmniDxWrapper:** ältere 32-Bit-Windows-Spiele und Legacy-APIs.
- **OmniVoodoo2:** DirectDraw, frühes Direct3D und 3Dfx Glide; das offizielle
  dgVoodoo2-Paket wird vom Nutzer bereitgestellt und per SHA-256 geprüft.
- **OmniVKD3D:** experimentelles Direct3D 12 über Vulkan, x86/x64.

## Drei nachvollziehbare Schritte

![OmniWrappers-Ablauf](assets/brand/workflow-1600x420.svg)

1. Die echte Spiel-EXE auswählen — keinen Launcher oder Shortcut.
2. Architektur, API, exakte DLL-Namen, Warnungen und Kollisionen prüfen.
3. Den freigegebenen Plan lokal im Spielordner installieren; Sicherung und
   hash-geprüftes Rollback bleiben verfügbar.

Die Consumer-Oberfläche ist offline, werbefrei, ohne Konto und ohne Telemetrie.
Sie bietet English, Deutsch, Español, Français und Română. Entwickler-, Wave-,
Benchmark- und Corpus-Werkzeuge sind nicht Teil der Consumer-Oberfläche.

![Alle vier OmniWrappers-Installer](assets/screenshots/omnivex-installer-collection.png)

## Freie Donationware

OmniWrappers ist kostenlos. Es gibt keine erforderliche Zahlung und
keine Werbung. Freiwillige Unterstützung finanziert Tests, Paketierung,
Dokumentation und Support.

<div align="center">
  <a href="https://www.patreon.com/TheOmniGrid"><img src="assets/brand/support-patreon.svg" height="64" alt="OmniWrappers auf Patreon unterstützen"></a>
  <a href="https://ko-fi.com/theomnigrid"><img src="assets/brand/support-kofi.svg" height="64" alt="OmniWrappers auf Ko-fi unterstützen"></a>
</div>

Fremdkomponenten behalten ihre eigenen Lizenzen und Rechte. Eine Spende macht
DXVK, dxwrapper, vkd3d-proton oder dgVoodoo2 nicht zu proprietärer
OmniWrappers-Software.

Version **1.0.0** ist ein getesteter Final Candidate. Die Auslieferungsdateien
sind noch nicht Authenticode-signiert; dieses Repository ist daher eine
Dokumentations- und Präsentationsseite, kein öffentlicher Download-Kanal.

Kontakt: `omnivex@theomnigrid.biz`
