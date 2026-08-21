# Compatibility guide

| Product | APIs | Architectures | Important limit |
|---|---|---|---|
| OmniDXVK | D3D8, D3D9, D3D10 Core, D3D11, DXGI | x86, x64 | Vulkan-capable driver required |
| OmniDxWrapper | DirectDraw/D3D8/9 plus legacy input, audio, media and system proxy APIs | x86 | Current Omni runtime is genuinely 32-bit |
| OmniVoodoo2 | DDraw/D3D1–9, Glide 1–3 | x86, x64, ARM64 where present upstream | Official hash-pinned packages must be supplied by user |
| OmniVKD3D | D3D12 | x86, x64 | Experimental native-Windows path |

## What changes results

Compatibility is specific to the game executable hash, game patch, GPU,
driver, operating system, overlay/injector set, mods and selected wrapper chain.
“Supported API” is not the same as “every title using that API is verified.”

## Best troubleshooting order

1. Confirm the real game EXE and architecture.
2. Remove unrelated overlays and third-party injected DLLs temporarily.
3. Use one wrapper product at a time.
4. Keep the automatic DLL recommendation unless a trusted game guide says otherwise.
5. Use **Check this game**, then **Test game**.
6. Roll back before trying a different plan.
7. Create a privacy-redacted support package if the failure remains.
