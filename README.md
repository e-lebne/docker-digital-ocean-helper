# Digital Ocean helper

This docker image is used to run commands against a Kubernetes cluster in Digital Ocean using the `doctl` tool.

## Releasing a new version

Git tags are following the tags of `doctl`. E.g. version 1.18.0 the digital-ocean-helper contains the `1.18.0` version of `doctl`. This has worked ok so far and we will try to keep tagging this way until we cannot do it anymore.

By setting a git tag a new image will be created and automatically uploaded to Docker Hub.
