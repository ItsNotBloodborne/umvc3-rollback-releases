UMVC3 ROLLBACK
made by itsnotbloodborne

Private release channel for update testing.

Release assets:
- UMVC3-Rollback-vVERSION.zip: complete installer package.
- update.json: version, immutable download URL, size and SHA-256.
- update.sig: detached RSA/SHA-256 signature of the exact manifest bytes.

The launcher pins the signing public key. No GitHub credentials or private
signing keys are included in the mod. Existing pre-updater installations need
one manual update before they can check for future versions.

This repository stays private until update-path testing is complete.
Anonymous update checks cannot access private GitHub assets. Private tests
download with the maintainer's GitHub CLI, then exercise the same verifier,
staging, updater worker and automatic installer against an isolated install.

No retail game files, crash dumps, or runtime source are hosted here.
Required library notices remain in the downloadable package's licenses folder.
