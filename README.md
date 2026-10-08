# Pro Algorithm — RedMark releases

Public release channel for the Pro Algorithm Revit add-in (כמויות ורשימות). The source is private;
this repository only carries the GitHub Releases that the installer and the add-in's self-update read.

- Installer: [`releases/latest/download/ProAlgorithm-RedMark-Setup.exe`](https://github.com/fleet-360/redmark-download/releases/latest/download/ProAlgorithm-RedMark-Setup.exe)
- Update manifest read by the add-in: `releases/latest/download/latest.json`

Releases are published automatically by the source repository's CI on every push to `main`.
Do not upload assets here by hand: the add-in verifies each zip against the SHA-256 in `latest.json`.
