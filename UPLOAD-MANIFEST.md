# GitHub upload manifest

Upload the contents of **this `GitHub/` directory only**.

Allowed:

- Markdown documentation
- Product icons, real installer screenshots and OmniVex brand graphics
- Repository metadata under `.github/`, `.gitignore`, and `.gitattributes`

Forbidden:

- Installer EXEs or runtime DLLs
- Wrapper or installer source code
- Build/test scripts and private evidence
- `Runtime`, `RuntimeArchives`, `dist`, `work`, `outputs`, `bin`, `obj`
- Certificates, private keys, Patreon/Ko-fi customer exports

The repository must contain no GitHub Release assets or binary download links.

Before the first push, run `git status --short` and verify every staged path by
eye. The included `.gitignore` is a safety net, not a substitute for review.
