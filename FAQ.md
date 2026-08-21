# Frequently asked questions

## Does OmniVex modify Windows globally?

No. The consumer installers write only beside the selected game EXE and keep
their backup/manifest data in that game directory.

## Is it an anti-cheat bypass?

No. OmniVex never bypasses, hides from or patches anti-cheat. Check the game
publisher's policy before adding any local wrapper DLL to a protected game.

## Why is OmniDxWrapper 32-bit only?

The current underlying runtime is x86. The installer refuses x64 targets rather
than pretending a same-named DLL is compatible.

## Why does OmniVoodoo2 ask for an official ZIP?

The author permits different forms of game-specific redistribution but places
limits on standalone bundling. Asking the user for the official package keeps
the general-purpose installer conservative and verifiable.

## Is payment required?

No. OmniVex tools are free donationware with no required payment and no ads.
Optional donations support testing, packaging, UI, documentation, and support.
Each third-party runtime keeps its own license and rights.

## Is source code on GitHub?

The private OmniVex installer source is not published there. Source availability
required by third-party MPL/LGPL components is handled separately and described
in `SOURCE-AVAILABILITY.md`.
