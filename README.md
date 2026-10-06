# Traqui city packs

This repository publishes versioned, **public reference geography** for
Traqui's optional offline city detection. It contains no profiles, GPS points,
trip histories, visit marks, or other user data. Downloading a pack does not
upload anything from a user's device.

The `cities-v1` release contains regional SQLite boundary packs. Each pack's
source country, attribution, original licence link, decompressed SHA-256 and
expected size are listed in [manifest.json](manifest.json). Traqui verifies the
checksum before installing a pack. The catalogs of eligible place IDs are
bundled with the app; the boundary packs are downloaded only when selected.

The source datasets have **different licences**. There is no blanket licence
that replaces their individual terms. Consult each country's attribution and
licence URL in the manifest before redistributing or adapting a pack. The
coverage is dated and partial: a missing settlement is not evidence that it
was not visited, and a nearest-name guess is never used for GPS marks.
