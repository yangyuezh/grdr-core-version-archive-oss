# OSS publication and license scope

This is an independent public copy of
[`yangyuezh/grdr-core-version-archive`](https://github.com/yangyuezh/grdr-core-version-archive),
prepared on **2026-10-24**. It preserves the original Git history, source trees,
branches and tags, including the archive's 43 audited version nodes from
v0.1.0 through v4.5.9. The source archive's main commit at copying was
`5d18aeaf21ac5631d6810c62a42b4f010f3de25c`.

## MIT grant

The copyright holder, YANG YUE, makes the original GRDR software code and
original project documentation that they own in this copy available under the
MIT License in [LICENSE](LICENSE). This grant includes that original work as
preserved in the historical commits and tags copied into this repository.

This publication appends a licensing commit to `main`. Historical commits and
tags are not rewritten; their hashes, authorship, dates, and source contents
remain unchanged. Consequently, a historical tag checkout retains the files
that existed at that time and may not itself contain a LICENSE file. Refer to
this publication notice and the LICENSE on this repository's main branch for
the license grant. The new grant does not imply that those historical versions
were publicly MIT-licensed on their original development dates.

## Third-party material

The MIT grant does **not** relicense third-party code, dependency packages,
external database content, copied source descriptions or metadata, observation
data, publications, or other material whose rights belong to another party.
In particular, historical UNdata and other data-source material remains subject
to the relevant provider's terms and any applicable third-party rights.
Preserve source attribution, provenance, and existing notices. Public access to
a source or inclusion in this archive is not a separate license grant for it.

## What is preserved and what is new

- The source archive's 63 reachable commits, 11 branches and 62 tags are
  preserved. The new `main` includes the original source `main` as an ancestor
  and adds only LICENSE and this notice; other branch tips and all tags retain
  their original object IDs.
- The 54 source GitHub Release records are recreated with the same tag names,
  titles, bodies and prerelease status. Six attached assets are copied with
  matching SHA-256 hashes. Original source references in documentation and
  release bodies are intentionally retained as provenance.
- GitHub assigns new repository/release/asset IDs, URLs and publication times.
  Stars, watches, forks, downloads, CI runs and other platform activity are not
  inherited. A newly copied Release is not evidence of a historical public
  release or prior public adoption of this OSS repository.
- The original source archive is not modified. This copy is a software-history
  archive; `main` is its audit entry point, and historical source trees are
  available through their preserved tags.

## Verification

Run from a complete clone with all tags:

```sh
python3 scripts/audit_archive.py
python3 scripts/audit_remote_releases.py --repository yangyuezh/grdr-core-version-archive-oss
```

The first command verifies the stored Git trees and version ledgers. The second
checks the 43 audited version Releases in this OSS repository. Neither command
asserts that every historical version can run in a current environment.
