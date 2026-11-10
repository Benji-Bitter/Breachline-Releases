# Releases

Versioned release records for Breachline. One folder per public version:

```
releases/
└── v0.x.y/
    ├── manifest.json      # build manifest (see manifest.example.json)
    ├── SHA256SUMS.txt     # checksums for every published artifact
    └── PATCH_NOTES.md     # full patch notes for the version
```

Packaged binaries themselves are attached to **GitHub Releases**, not committed
to this repository — this tree holds the records that verify and describe them.

See [`manifest.example.json`](manifest.example.json) for the manifest format.
