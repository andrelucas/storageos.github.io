---
layout: guide
title: Docker image reference
anchor: reference
module: reference/docker_image
---


# Docker Image Reference

There is a single StorageOS Docker image that provides multiple functions:

* The *control plane* is responsible for cluster configuration and administration.  It contains the API, the Web console, scheduler, message bus and key-value store persistence.
* The *data plane* handles all data access.  It is made up of various components such as the director, DirectFS, and pluggable storage drivers.
* The *docker client* allows any Docker host to mount storage from a remote StorageOS cluster.
* The *command-line interface (CLI)* can be used for administration and maintenance tasks.

## Controlplane

To run the StorageOS control plane, specify the `server` parameter:

```bash
docker run
```


