# jammy

Creates multi-arch (amd64 and arm64) builder images from ubuntu jammy using base images from [jericop/cnb-base](https://github.com/jericop/cnb-base).

These builders do not have buildpacks so they must be specified at build time.

# Publishes the following images

## github container registry

* `ghcr.io/jericop/builder-jammy`

## docker hub

* `jericop/builder-jammy`

# Image tags

* `stack`
  * see `builder-stack.toml`
* `target`
  * see `builder-target.toml`
* `latest`
  * see `builder-latest.toml`
  * This is meant for backward compatibility because it includes stack and new base (run/build) images
