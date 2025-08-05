# Hello World

This is an example/testing repository for auto Docker image build and push to GitHub Container Registry (GHCR).

When the value of `version.txt` (containing a `semver` value, without line break at the end) is bumped, a GitHub Actions workflow is run to tag the commit, build the image with tags and labels, push it to GHCR and create a release note.

## Reference materials

- [Publishing Multi-Arch Docker images to GHCR using Buildx and GitHub Actions](https://dev.to/pradumnasaraf/publishing-multi-arch-docker-images-to-ghcr-using-buildx-and-github-actions-2k7j)
