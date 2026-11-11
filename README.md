# Clinicbank releases

Signed update files for Clinicbank, read by **Clinicbank Setup** ("Check for updates") at the clinics.

- `index.json`: the list of the newest update for each edition, signed in `index.sig` with the seller's key.
- `files/*.bankupdate`: the update files, each signed on its own.

Clinicbank Setup uses a file only when both signatures check out. This repository holds no code, no keys and no clinic data.
Published with `release.ps1` from the Clinicbank source.
