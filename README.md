# NoticeAll Updates

This public repository hosts Sparkle update metadata and release downloads for
NoticeAll. The application source remains in a separate private repository.

## Channels

- `appcast.xml`: stable production channel. Published only for notarized public
  releases.
- `test/appcast.xml`: prerelease integration channel used to verify the complete
  GitHub download, signature, replacement, and relaunch path.

Release archives are signed with Sparkle EdDSA and Developer ID. The Sparkle
private key, Developer ID credentials, and notarization credentials are never
stored in this repository.

The test channel and prerelease downloads are verification artifacts, not
customer releases.
