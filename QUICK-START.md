# Quick start

1. Close the game and extract/run the correct OmniWrappers installer.
2. Pick your language in the upper-right corner.
3. Select the **real game executable**. Avoid launchers, setup programs,
   shortcuts and crash reporters.
4. Leave **Automatic API/DLL naming** enabled.
5. Read the architecture and DLL preview. Resolve any warning shown.
6. Keep backup enabled and choose **Install smart plan**.
7. Launch the game. If it fails, use **Roll back** before trying another wrapper.

## Which installer should I try?

- D3D8–11 on a Vulkan-capable GPU: **OmniDXVK**.
- Older 32-bit Windows/API problem: **OmniDxWrapper**.
- DirectDraw, early Direct3D or Glide: **OmniVoodoo2**.
- D3D12 through Vulkan experimentation: **OmniVKD3D**.

## OmniVoodoo2 package step

The general-purpose installer does not embed dgVoodoo2. Download the official
2.87.3 ZIP from [the upstream release](https://github.com/dege-diosg/dgVoodoo2/releases/tag/v2.87.3). Put `dgVoodoo2_87_3.zip` next to the
installer or in Downloads. For an x64/ARM64 game, also provide
`dgVoodoo2_87_3_dev64.zip`. Omni verifies pinned hashes before using them.

## If the game is protected

Stop and check the publisher's policy. OmniWrappers never bypasses anti-cheat. A
local wrapper can still be prohibited or trigger a protection system even when
it is technically harmless.
