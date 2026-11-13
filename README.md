# Babble textured emojis

Client review and delivery repository for Babble's textured animated emojis.

This snapshot contains **1,444 owner-approved animations across 516 designs**
(4,578,781,588 animation bytes). It is a partial approved collection from the
2,241-variation upstream source. Missing designs or tones are not delivered here.

## Layout and provenance

`assets/` mirrors the exact design folders, tone folders and animation filenames
of [Microsoft Fluent Animated Emoji](https://github.com/microsoft/fluentui-emoji-animated/tree/daa0365c09795789ed2bc6e8b228c97736cb6669)
at commit `daa0365c09795789ed2bc6e8b228c97736cb6669`. Original per-design metadata is retained unchanged. Animation
files contain Babble's exact selected owner-approved bytes at native 256 x 256.
This repository preserves source layout; it does not mirror upstream Git history.

`manifest.json` lists output hashes, variation coverage, source paths and approval
scope. `checksums.sha256` verifies animation and metadata bytes after LFS download.
Approval evidence hashes identify the private evidence without publishing internal
paths, notes, credentials or client review records.

## Download the animations

Install Git and Git LFS, then run:

```sh
git lfs install
git clone https://github.com/Krimsonhouse/Babble-textured-emojis.git
cd Babble-textured-emojis
git lfs pull
git lfs fsck
```

Use a Git LFS checkout for delivery. GitHub source ZIPs may contain pointer files
depending on repository archive settings. A small text file beginning with
`version https://git-lfs.github.com/spec/v1` is a pointer, not an animation.

## Approval scope

Owner approval is recorded for every included exact hash. Client acceptance and
motion qualification vary; inspect each manifest entry. This snapshot does not
assert release authorization or a technical pass for assets with unresolved
qualification. Client decisions on older hashes do not approve revised files.

Upstream artwork and metadata carry Microsoft's MIT notice, retained in `LICENSE`.
