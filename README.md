# clamav-db

ClamAV signature mirror (main, daily, bytecode + `.cvd.sign`), refreshed every 4 hours by GitHub Actions with
[cvdupdate](https://github.com/Cisco-Talos/cvdupdate) and served by GitHub Pages. The signatures are public data.

Used as `PrivateMirror` by a server whose region the ClamAV CDN blocks.
