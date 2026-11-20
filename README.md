# Dexar Tracker releases

Signed update packages for Dexar Tracker. The app checks
`releases/latest/download/latest.json` and installs an update only if its
signature matches the key built into the app.

Source code is private. Releases are published from the maintainer's machine
with `bun run release` (see `docs/releasing.md` in the source repository).
