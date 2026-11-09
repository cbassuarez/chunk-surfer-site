# chunk-surfer-site

Public presentation assets used by the [Chunk Surfer itch.io page](https://cbassuarez.itch.io/chunk-surfer).

This repository hosts the storefront's display fonts, instrument materials, control states, and kiosk artwork. The game is distributed through its official itch.io page. Game source and repository history are outside this export.

The asset paths under `docs/media/storefront/` are kept stable for the storefront. Pin deployed asset URLs to an immutable commit. `asset-manifest.json` records the exported skin assets' byte counts and SHA-256 digests. Screenshot and brand manifests sit beside their respective files.

See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) and the bundled font notices for attribution and licensing information. This repository does not assign one blanket license to all materials.

[Report a bug](https://github.com/cbassuarez/chunk-surfer-site/issues/new?labels=bug) · [Send playtest feedback](https://github.com/cbassuarez/chunk-surfer-site/issues/new?labels=feedback)

## Storefront source

`itch/description.html`, `itch/theme.css`, and `itch/install-instructions.html` contain the presentation markup, custom CSS, and installation copy. Published navigation uses full same-page URLs because itch.io removes fragment-only hrefs. Local review copies use fragments so they remain in the preview. Display textures and fonts are pinned to an immutable asset commit; gameplay screenshot metadata is recorded alongside the screenshots.

The game is still distributed from itch.io. This repository keeps the page and public support links independent of the game source repository.
