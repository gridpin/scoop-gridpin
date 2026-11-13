# Scoop bucket for GridPin

[GridPin](https://gridpin.dev) is an offline geocoder: a country in a file, addresses to coordinates without a network.

```console
> scoop bucket add gridpin https://github.com/gridpin/scoop-gridpin
> scoop install gridpin
> gridpin --version
```

The manifest installs the prebuilt Windows x86_64 program of a [GitHub release](https://github.com/gridpin/gridpin/releases)
and checks its SHA-256. Country files are downloaded separately: see [the documentation](https://gridpin.dev/docs).

The manifest is generated from the release; issues go to [gridpin/gridpin](https://github.com/gridpin/gridpin/issues).
Licence of this repository: Apache-2.0.
