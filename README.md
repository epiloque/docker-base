# [stack-tools](https://github.com/escapace/stack-tools)

[![build status](https://secure.travis-ci.org/escapace/stack-tools.png)](https://travis-ci.org/escapace/stack-tools)
[![license](https://img.shields.io/badge/license-Mozilla%20Public%20License%20Version%202.0-blue.svg)](<>)

Collection of [manage](https://github.com/escapace/manage) modules shared by projects across the escapace stack.

## `docker/dockerBuild`

A directory structure convention for building docker images.

| Environment Variable   |   Default  | Description           |
| ---------------------- | :--------: | --------------------- |
| `DOCKER_DIRECTORY`     |  `images`  | Dockerfiles directory |
| `DOCKER_SCOPE`         | `internal` | Docker image scope    |
| `DOCKER_BUILD_OPTIONS` |   `--rm`   | Docker build options  |

## `docker/downloadGosu`

Download and verify [gosu](https://github.com/tianon/gosu) - makes it less of a pain to
 switch to other users without introducing a `su` or `sudo` intermediate
 process.

| Environment Variable |                        Default                       | Description  |
| -------------------- | :--------------------------------------------------: | ------------ |
| `GOSU_VERSION`       | […](/scripts/modules/stack-tools/stackToolsDefaults) | gosu version |

## `docker/downloadTini`

Download and verify [tini](https://github.com/krallin/tini) - spawns a single child, and wait for it to exit all the while reaping zombies and performing signal forwarding.

| Environment Variable |                        Default                       | Description  |
| -------------------- | :--------------------------------------------------: | ------------ |
| `TINI_VERSION`       | […](/scripts/modules/stack-tools/stackToolsDefaults) | tini version |

## `hashicorp/downloadPacker`

Download and verify HashiCorp’s [packer](https://www.packer.io) - a tool for creating identical machine images for multiple platforms from a single source configuration.

| Environment Variable |                        Default                       | Description    |
| -------------------- | :--------------------------------------------------: | -------------- |
| `PACKER_VERSION`     | […](/scripts/modules/stack-tools/stackToolsDefaults) | packer version |

## `hashicorp/downloadTerraform`

Download and verify HashiCorp’s [terraform](https://www.terraform.io/) - safely and predictably create, change, and improve infrastructure.

| Environment Variable |                        Default                       | Description       |
| -------------------- | :--------------------------------------------------: | ----------------- |
| `TERRAFORM_VERSION`  | […](/scripts/modules/stack-tools/stackToolsDefaults) | terraform version |

## `restic/downloadRestic`

Download and verify [restic](https://github.com/restic/restic) - fast, secure, efficient backup program.

| Environment Variable |                        Default                       | Description    |
| -------------------- | :--------------------------------------------------: | -------------- |
| `RESTIC_VERSION`     | […](/scripts/modules/stack-tools/stackToolsDefaults) | restic version |

## License

This program is free software: you can redistribute it and/or modify it under
the terms of the [MPL 2.0](/LICENSE).
