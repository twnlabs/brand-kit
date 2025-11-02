# Releases

1) Prepare assets
- Ensure `logos/`, `collection_logo/`, `icons/`, `banners/`, `wallpapers/` are populated and filenames follow snake_case.
- Verify SVGs render correctly; PNGs have transparent backgrounds where applicable.

2) Version bump and tag
- Follow SemVer (e.g., `v1.0.0`).
- Create a Git tag for the release: `git tag v1.0.0 && git push --tags`.

3) Build a zip bundle
- Include the directories above and `LICENSE.md`, `TRADEMARKS.md`.
- Suggested name: `twnlabs-brand-kit-v1.0.0.zip`.

4) Publish
- Create a GitHub Release with the tag and upload the zip.
- Release notes: list new/updated assets and any removals/deprecations.

5) (Optional) Checksums
- Provide SHA256 for the uploaded zip to allow integrity verification.
