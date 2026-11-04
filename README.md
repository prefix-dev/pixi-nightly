# pixi-nightly

Development builds of [pixi](https://github.com/prefix-dev/pixi), one release per push to `main`.

The binaries are signed like regular pixi releases. Each release is tagged with `git describe` output, e.g. `v0.81.0-65-g619b0a3f6`.

Releases are created by [`dev-release.yml`](https://github.com/prefix-dev/pixi/blob/main/.github/workflows/dev-release.yml) in prefix-dev/pixi. Its token for this repository comes from [octo-sts](https://github.com/octo-sts/app); the trust policy is [`.github/chainguard/pixi-dev-release.sts.yaml`](.github/chainguard/pixi-dev-release.sts.yaml).
