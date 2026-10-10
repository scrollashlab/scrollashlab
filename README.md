# Scroll Ash Lab

Independent open-source lab working on the [Vesuvius Challenge](https://scrollprize.org): small tested fixes for the [ScrollPrize/villa](https://github.com/ScrollPrize/villa) codebase, audits of the open data, and pre-registered tests. AI-assisted.

- **villa-fixes (canonical):** https://gitlab.com/scroll-ash-lab/villa-fixes
- **villa-fixes (GitHub mirror):** https://github.com/scrollashlab/villa-fixes
- **X:** [@ScrollAshLab](https://x.com/ScrollAshLab)
- **Contact:** scrollash.lab@gmail.com

## Highlights

- [`xframe`](https://gitlab.com/scroll-ash-lab/villa-fixes/-/tree/main/xframe): CPU CLI for the open data's cross-frame tifxyz meshes. 902/902 published cross-frame meshes reproduce point by point from their source mesh and the catalog.
- [`sv-canvas-1727`](https://gitlab.com/scroll-ash-lab/villa-fixes/-/tree/main/sv-canvas-1727): 692/692 published surface volumes reproduce their canvas size from the mesh the catalog names (villa #1727).
- [`villa-downscale`](https://gitlab.com/scroll-ash-lab/villa-fixes/-/tree/main/villa-downscale): patch so the `vesuvius` package applies the open data's `original_volume_downscale`; pre-registered before/after on 23/23 published meshes.
- [`catalog-qa-audit`](https://gitlab.com/scroll-ash-lab/villa-fixes/-/tree/main/catalog-qa-audit): catalog metadata vs mesh points across 1,531 meshes; 15 segments declare a size that doesn't match their mesh.
- [`gpu-1648-heldout`](https://gitlab.com/scroll-ash-lab/villa-fixes/-/tree/main/gpu-1648-heldout) and [`gpu-1648-intermediate-scale`](https://gitlab.com/scroll-ash-lab/villa-fixes/-/tree/main/gpu-1648-intermediate-scale): pre-registered GPU tests of the villa #1648 in-plane-scale warning; the warning held on 3/3 segments in each test.
- [`bucket-pyramid-audit`](https://gitlab.com/scroll-ash-lab/villa-fixes/-/tree/main/bucket-pyramid-audit): in 18 of 76 ink render stores in the `scrollprize/datasets` bucket, level 1 holds only the first 33 of 65 depth planes.
- [`500p2a-label-alignment`](https://gitlab.com/scroll-ash-lab/villa-fixes/-/tree/main/500p2a-label-alignment): rigid label misalignment ruled out as the cause of chance-level ink scores on 500p2a.

Write-ups, caveats and reproduction notes: [`docs/prize-writeups/`](https://gitlab.com/scroll-ash-lab/villa-fixes/-/tree/main/docs/prize-writeups). Code is MIT; open data stays CC BY-NC 4.0 at source and is not redistributed.
