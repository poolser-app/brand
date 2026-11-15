# Poolser brand

Shared visual identity for [Poolser native](https://github.com/poolser-app/native), the [browser app](https://github.com/poolser-app/web) and the [public website](https://github.com/poolser-app/website).

- [Brand reference](BRAND.md): character, palette, typography, Soft Crest, accessibility and motion.
- [Colour tokens](tokens/colors.json): light/dark semantic colours, range statuses, wallet colours and water opacity.
- [Original character](assets/PoolserCharacter.png) and [compact logo](assets/AppLogo.png).
- Apple exports: [app icons](assets/apple/AppIcon.appiconset) and [logo image set](assets/apple/AppLogo.imageset).

## Adoption

Use a reviewed full commit SHA. Copy only the files the consumer needs, record their source paths and SHA-256 hashes, and commit those copies with the application. Keep builds independent of network access to this repository. Adopt updates through an explicit application PR.

The native application documents its pinned snapshot and update command in `docs/brand/README.md`. SwiftUI code, native layout rules, screenshot generators and product screenshots remain in native. This repository holds shared identity and artwork; it does not publish the product website or implement financial calculations.

## Provenance

Initial identity and every image/asset-catalog export were imported from [poolser-app/native at `24d557a`](https://github.com/poolser-app/native/tree/24d557a9237dc4a8bc6685ec652af9fcf97816ea). The images and asset catalogs are byte-for-byte copies of the existing native resources. Colour tokens preserve the values in `Sources/PoolserKit/Presentation/GraphitePalette.swift` at that commit.

The guide separates shared identity from native implementation instructions. The first import changes no shipped artwork, colours or app behaviour. See [LICENSE](LICENSE) for the existing project license; no font files are included.
