# chunk-surfer-site

Public presentation assets used by the [Chunk Surfer itch.io page](https://cbassuarez.itch.io/chunk-surfer).

This repository hosts the storefront's display fonts, instrument materials, control states, and kiosk artwork. The game is distributed through its official itch.io page. Game source and repository history are outside this export.

The asset paths under `docs/media/storefront/` are kept stable for the storefront. Pin deployed asset URLs to an immutable commit. `asset-manifest.json` records the exported skin assets' byte counts and SHA-256 digests. Screenshot and brand manifests sit beside their respective files.

See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) and the bundled font notices for attribution and licensing information. This repository does not assign one blanket license to all materials.

[Report a bug](https://github.com/cbassuarez/chunk-surfer-site/issues/new?labels=bug) · [Send playtest feedback](https://github.com/cbassuarez/chunk-surfer-site/issues/new?labels=feedback)

## Storefront source

`itch/description.html`, `itch/theme.css`, and `itch/install-instructions.html` contain the presentation markup, custom CSS, and installation copy. Published navigation uses full same-page URLs because itch.io removes fragment-only hrefs. Local review copies use fragments so they remain in the preview. Display textures and fonts are pinned to an immutable asset commit; gameplay screenshot metadata is recorded alongside the screenshots.

The game is still distributed from itch.io. This repository keeps the page and public support links independent of the game source repository.

## Selected promotional images

`docs/media/storefront/promo/` holds the selected social image and 21:9 wide cover with image hashes. The social composition uses the Albion van, VFD title and Ellery exterior; the wide composition uses Source architecture. Both were composited from existing game captures and assets without generative imagery. Readout and installation prose use the native VFD font; phone-width text panels expand with their copy.

## Storefront copy

The current review copy leads with Ellery’s night and people, uses the recording commission as the point of entry, and shows the journey’s breadth without explaining its causes. `itch/short-description.txt` contains the project tagline. Captions expand to keep the complete VFD prose visible on desktop as well as smaller screens. Reader validation is separate from source and layout checks.
