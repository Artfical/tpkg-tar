# tar

GNU tar 1.35 (gzip and bzip2 through the gzip and bzip2 packages)

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install tar
```

| | |
|---|---|
| Version | 1.35 |
| Licence | GPL-3.0-or-later |
| Upstream | - |
| Needs | [`gzip`](https://github.com/Artfical/tpkg-gzip), [`bzip2`](https://github.com/Artfical/tpkg-bzip2) |
| Needs tOS build | 619 or newer |
| Size | 244019 bytes (491928 unpacked) |
| SHA-256 of the `.tpkg` | `8ca7c0c6826d3582b7811dd6976cc9ac9b39a9b397b9e2aeaaea337ac5a34545` |

## Commands it adds

| Command | Runs |
|---|---|
| `tar` | `bin/tar` |

## Download

The package file (`tar-1.35.tpkg`) and the sources it was built from are the assets of the
[v1.35 release](https://github.com/Artfical/tpkg-tar/releases/tag/v1.35).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `tar-1.35.tar.xz`

Check a download: `sha256sum tar-1.35.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: GPL-3.0-or-later. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
