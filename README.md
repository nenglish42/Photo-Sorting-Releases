# Photo Sorting for Windows

This repository hosts official versioned Windows installers, portable packages, release notes and SHA-256 checksums. Application source is maintained separately.

Download published versions from [Releases](https://github.com/nenglish42/Photo-Sorting-Releases/releases). The first release is being prepared; no installer is published yet.

Choose the x64 MSI for a per-user Windows installation, or extract the complete portable ZIP into its own folder. Development Python is not required. Keep distribution.json beside PhotoSorting.exe and the _internal folder.

Stable releases contain a matching MSI, portable ZIP and SHA256SUMS.txt. Verify the downloaded package against the published SHA-256 before installation.

Descriptor-aware installed versions check stable GitHub releases, download and verify their matching package, then prompt you to save work and restart to update.

AI and account usage require authenticated Cloud sign-in. Provider and storage credentials remain on the server. The release-publishing credential is stored in the private source repository's Actions secrets.
