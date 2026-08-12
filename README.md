# iOS 27 firmware diffs

Browsable firmware-diff payloads for iOS 27, published from
[`blacktop/ipsw-diffs`](https://github.com/blacktop/ipsw-diffs).

## Available diffs

- [26.5 (23F77) vs. 27.0 (24A5355q)](diffs/26_5_23F77_vs_27_0_24A5355q/README.md)
  ([manifest](manifests/26_5_23F77_vs_27_0_24A5355q.json))
- [27.0 (24A5355q) vs. 27.0 (24A5370h)](diffs/27_0_24A5355q_vs_27_0_24A5370h/README.md)
  ([manifest](manifests/27_0_24A5355q_vs_27_0_24A5370h.json))
- [27.0 (24A5370h) vs. 27.0 (24A5380h)](diffs/27_0_24A5370h_vs_27_0_24A5380h/README.md)
  ([manifest](manifests/27_0_24A5370h_vs_27_0_24A5380h.json))
- [27.0 (24A5380h) vs. 27.0 (24A5390f)](diffs/27_0_24A5380h_vs_27_0_24A5390f/README.md)
  ([manifest](manifests/27_0_24A5380h_vs_27_0_24A5390f.json))
- [27.0 (24A5390f) vs. 27.0 (24A5408d)](diffs/27_0_24A5390f_vs_27_0_24A5408d/README.md)
  ([manifest](manifests/27_0_24A5390f_vs_27_0_24A5408d.json))

## Layout

- `diffs/` contains the browsable Markdown payload.
- `manifests/` contains machine-readable provenance and integrity metadata.
- `track.json` contains the reviewed iOS 27 selector and merged baseline.

## Discovery

The manual, read-only discovery workflow calls the catalog detector at an
immutable commit. It accepts no OS, device, major, or build overrides and does
not download firmware, generate diffs, push branches, or open pull requests.

This repository is an initial sharding pilot. The source repository remains the
authoritative legacy corpus until the migration catalog and publication workflow
are validated end to end.
