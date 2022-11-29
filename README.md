# Docker
Docker image builder for Kreato Linux.

# How it works
It downloads the latest rootfs artifacts from [nyaastrap](https://github.com/kreatolinux/nyaastrap), extracts em and pushes the rootfs as a Docker image to the registry.

It does this once a week (00:00 UTC Sunday to be exact) but sometimes it might be ran manually by us.

# Download images
We currently offer 2 images.

* [kreato/linux that has no compiler](https://hub.docker.com/r/kreato/linux)
* [kreato/builder that has a compiler](https://hub.docker.com/r/kreato/builder)
