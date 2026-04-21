# scoop-bucket

Official Scoop bucket for [Spot](https://github.com/spot-nyc/spot) on Windows.

## Install

```powershell
scoop bucket add spot-nyc https://github.com/spot-nyc/scoop-bucket
scoop install spot
```

## Update

```powershell
scoop update spot
```

## Uninstall

```powershell
scoop uninstall spot
```

## What's in this repo?

Only the auto-generated Scoop manifest for `spot`, in `bucket/spot.json`. It is updated automatically by [GoReleaser](https://goreleaser.com) every time a new tag is pushed to [spot-nyc/spot](https://github.com/spot-nyc/spot). Please don't edit the manifest by hand — changes will be overwritten on the next release.

For source code, issues, and documentation, see the main [spot-nyc/spot](https://github.com/spot-nyc/spot) repo.
