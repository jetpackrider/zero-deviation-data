# Zero Deviation data

Per-state data files for the [Zero Deviation](https://github.com/jetpackrider/district-zeroing-extension) browser extension, served by GitHub Pages at `https://jetpackrider.github.io/zero-deviation-data/v1/<STATE>/manifest.json`.

Each state folder holds a `manifest.json` and the files it names: block populations, counties, precincts, towns, a water flag, block adjacency with shared border lengths, and block shapes per county. File names carry their SHA-256, so a file never changes once published. The format is described in the extension repo under [`docs/BUNDLE_FORMAT.md`](https://github.com/jetpackrider/district-zeroing-extension/blob/main/docs/BUNDLE_FORMAT.md), and the files are built and validated by its [`pipeline`](https://github.com/jetpackrider/district-zeroing-extension/tree/main/pipeline).

All 50 states and DC, 2020 census blocks.

## License and credit

These files contain data adapted from [Dave's Redistricting](https://github.com/dra2020) ([vtd_data](https://github.com/dra2020/vtd_data), [block_data](https://github.com/dra2020/block_data)), which is shared under CC BY-SA 4.0. They are shared under the same license, [CC BY-SA 4.0](LICENSE). Do not sell. Block shapes and census counts are from the U.S. Census Bureau and are in the public domain. Each manifest lists the exact source files it was built from.

Not affiliated with or endorsed by Dave's Redistricting.
