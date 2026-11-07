# About this fork

This is a fork of [josiahg2502-glitch/SuperMarioWonderRecomp](https://github.com/josiahg2502-glitch/SuperMarioWonderRecomp), maintained by Bakanda07 as a continuation of the open-source project. It carries the upstream work as it stood on the date below.

- Game / target: Super Mario Bros. Wonder (Switch, NVN to Vulkan)
- Licence: MIT. The licence file and the author notices of the upstream repository are kept as they are.
- Base commit: `8395d322101dc4f9b83672619be5bcddf3070f31` (8395d32, 2026-11-02: "DEBUG-2 #93: Toadette checked in play, both eyes")
- Base tag: `upstream-base-2026-11-07` marks that commit in this repository.
- Default branch: `main`

## What differs from upstream

None. `main` is identical to upstream at the base commit.

## Releases and mirrors

No release upstream, so none mirrored. Most of the framework is the work of BelmanteGu (SwitchGamesRecomp); keep that credit.

Releases published here before any change of ours are copies of the upstream builds. They are not built from this repository.

## Following upstream

```sh
git fetch upstream
git log --oneline main..upstream/main
git merge --ff-only upstream/main
```

## Rules for this fork

- No game data, keys, extracted files or code generated from a game goes into this repository.
- A release built from this fork must say so in its name or notes and give the base tag it started from.
- Changes of ours are listed in the section above when they are merged.
