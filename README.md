# ServerCreator — Releases

This repository hosts the official **setup files** for
ServerCreator by **X1NPAR1**.

The ServerCreator application checks this repository's **latest Release** on
every launch. When a newer version is published here, the app offers an in-app
update: it downloads the setup `.exe` attached to the latest release and runs it
automatically after your approval.

## Publishing a new version (for X1NPAR1)
1. In the source repo, push a tag `vX.Y.Z`. The CI builds the installer and
   uploads it as a workflow artifact (`ServerCreator-Setup`).
2. Download that artifact.
3. Create a new **Release** in this repository with tag `vX.Y.Z` and attach the
   `ServerCreator-Setup-X.Y.Z.exe` file.

That is all — every running copy of ServerCreator will detect the new release.

## Current version
**v1.75.2**
