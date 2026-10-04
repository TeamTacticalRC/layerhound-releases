# LayerHound releases

Signed release packages for **LayerHound**, the print farm and home lab dashboard by Team Tactical RC.

LayerHound boards check this repository once a day for a newer version. They show the release notes in **Settings → About**, and install an update only when an admin presses **Update now**.

## Files in each release

| File | What it is |
|---|---|
| `layerhound-X.Y.Z.tar.gz` | The complete LayerHound application: backend and built dashboard. |
| `layerhound-X.Y.Z.tar.gz.sig` | Ed25519 signature of the package. |
| `manifest.json` | Version, SHA-256 checksum, and whether the board setup must run again. |

Boards install a package only if its signature matches the Team Tactical RC release key built into LayerHound. Packages from anywhere else are refused.

## Notes

- This repository holds only release packages; development happens elsewhere.
- No license has been chosen yet, so all rights are reserved. Please don't redistribute these packages.
- To report a security problem, see the security policy in the release notes or contact Team Tactical RC.
