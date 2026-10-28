# Cutgraph build inputs

Byte-exact mirrors of the third-party source archives used to build Cutgraph Studio releases, including the complete corresponding source of the bundled LGPL FFmpeg build and its dependencies.

Some upstream hosts generate source archives on demand, so the same commit downloads with different bytes each time. Each file here is the exact archive whose SHA-256 is pinned in [`installer/sources.json`](https://github.com/cutgraph/cutgraph/blob/main/installer/sources.json) in the main repository. Every build verifies that hash before using a file.

- Files are attached to tagged releases and never replaced. A new set of pins gets a new release.
- Asset names are `<sha256>-<upstream version>.<ext>`.
- Each archive keeps its upstream licence. See `installer/sources.json` for the licence, upstream URL and version of every input.

This repository contains no Cutgraph code. Report problems at https://github.com/cutgraph/cutgraph.
