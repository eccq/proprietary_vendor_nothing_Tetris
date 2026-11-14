# Changelog

Changes to the DescartesOS vendor tree for the CMF Phone 1 (Tetris), relative to
lufrz's `lineage-24.0` tree it was taken from.

## v1.0 (2026-11-13)

- Dropped the `vendor.mediatek.hardware.lbs@1.0` prebuilt from `Android.bp`
  and its entry from `Tetris-vendor.mk`. DescartesOS builds that interface from
  `hardware/mediatek/interfaces/hardware/lbs/1.0`, so the prebuilt was a
  duplicate module.
- Added README and credits.
