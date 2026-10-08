# Sofie Control checkpoint

Current working Android package: `com.sofie.control.v31`

## Version 3.8
- Based on stable 3.7 Marketplace and Facebook Groups explorer.
- Keeps Marketplace location/radius filtering.
- Adds persistence of the last Marketplace result list.
- Adds `marketplace otevri N` to reopen a specific saved Marketplace result.
- Adds `marketplace odkaz N` to resolve a direct Facebook Marketplace permalink for a saved result.
- Link resolution first scans Accessibility node text/content descriptions/extras for `facebook.com/marketplace/item/<id>`.
- If Facebook does not expose a permalink directly, it opens the listing and attempts Share -> Copy link, then reads/canonicalizes the copied URL.
- Marketplace cards also include a direct URL immediately when Facebook exposes one in Accessibility data.

Build target: Android minSdk 26, targetSdk 34.
Signing certificate SHA-256: `10b81d9cd970659b6a2d51f406f4a1a08b312b0e89d3d76dec5b39080c80983f`.

Do not commit the private signing keystore to this public repository.
