# Sofie Control checkpoint

Current working Android package: `com.sofie.control.v31`

## Version 3.9
- Based on stable 3.7 Marketplace and Groups explorer.
- Keeps Marketplace location/radius filtering and saved result sessions.
- Fixes `marketplace odkaz N` / `marketplace otevri N` when Facebook takes time to reload search results.
- Waits for Marketplace result cards before matching the saved item.
- Adds gesture-based scrolling fallback when Facebook does not expose a scrollable Accessibility node.
- Uses more tolerant matching by saved title + price across Accessibility descendants/ancestors.
- After opening the selected listing, still attempts direct permalink extraction first, then Share -> Copy link.

Build target: Android minSdk 26, targetSdk 34.
Package: `com.sofie.control.v31`
Version code/name: `39 / 3.9`
Signing certificate SHA-256: `10b81d9cd970659b6a2d51f406f4a1a08b312b0e89d3d76dec5b39080c80983f`.

Do not commit the private signing keystore to this public repository.
