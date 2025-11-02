# TWN Labs — Brand Kit (Standalone)

Simple, modular structure for public brand assets. Keep this repo lightweight.

- Primary license: CC BY 4.0 (assets). See `LICENSE.md`.
- Trademarks: see `TRADEMARKS.md`.

## Structure

- `logo/svg/` — Vector logos (preferred for digital/print)
- `logo/png/` — Raster logos (transparent)
- `collection_logo/svg/` — Collection symbols (SVG)
- `collection_logo/png/` — Collection symbols (PNG)
- `wordmark/` — TWN wordmark (SVG/PNG)
- `icons/` — App/site icons
- `banners/` — Hero/OG/social banners
- `wallpapers/` — Desktop/mobile wallpapers
- `guides/` — Usage guide and notes

## Populate assets

Source existing files from `public_html/assets/twnlabs_brand_kit/`:
- Copy SVGs → `logo/svg/`
- Copy PNGs → `logo/png/`
- Copy collection logos (SVG) → `collection_logo/svg/`
- Copy collection logos (PNG) → `collection_logo/png/`
- Copy wordmark (SVG/PNG) → `wordmark/`
- Copy icons → `icons/`
- Copy hero/OG images → `banners/`
- Copy wallpapers → `wallpapers/`

## Naming

- Collections: `twnlabs_{tier}_collection_logo.svg|png` (e.g., `twnlabs_gold_collection_logo.svg`)
- Wordmark: `twnlabs_wordmark.svg|png` (variants: `twnlabs_wordmark_dark.svg`, `twnlabs_wordmark_light.svg`)

## Usage

See `guides/USAGE.md` for brand colors, spacing/minimum sizes, backgrounds/contrast, and FAQ.

## Versioning & Releases

- Tag releases using SemVer (e.g., `v1.0.0`).
- See `VERSIONING.md` and `RELEASES.md`.
