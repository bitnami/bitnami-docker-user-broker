[![CircleCI](https://circleci.com/gh/bitnami/bitnami-docker-user-broker/tree/master.svg?style=shield)](https://circleci.com/gh/bitnami/bitnami-docker-user-broker/tree/master)

# What is User-broker?

The [Service Catalog project](https://github.com/kubernetes-incubator/service-catalog/) is in incubation to bring integration with service brokers to the Kubernetes ecosystem via the [Open Service Broker API](https://github.com/openservicebrokerapi/servicebroker). User Broker is a part of the Service Catalog project.

There are two different images: [`service-catalog`](https://github.com/bitnami/bitnami-docker-service-catalog) and [`user-broker`](https://github.com/bitnami/bitnami-docker-user-broker)

# TL;DR;

User Broker is part of the Service Catalog that installs into a Kubernetes cluster and runs behind the [Kubernetes API Aggregator](https://kubernetes.io/docs/concepts/api-extension/apiserver-aggregation/).

# Why use Bitnami Images?

* Bitnami closely tracks upstream source changes and promptly publishes new versions of this image using our automated systems.
* With Bitnami images the latest bug fixes and features are available as soon as possible.
* Bitnami containers, virtual machines and cloud images use the same components and configuration approach - making it easy to switch between formats based on your project needs.
* Bitnami images are built on CircleCI and automatically pushed to the Docker Hub.
* All our images are based on [minideb](https://github.com/bitnami/minideb) a minimalist Debian based container image which gives you a small base container image and the familiarity of a leading linux distribution.

# Why use a non-root container?

Non-root container images add an extra layer of security and are generally recommended for production environments. However, because they run as a non-root user, privileged tasks are typically off-limits. Learn more about non-root containers [in our docs](https://docs.bitnami.com/containers/how-to/work-with-non-root-containers/).

# Supported tags and respective `Dockerfile` links

> NOTE: Debian 8 images have been deprecated in favor of Debian 9 images. Bitnami will not longer publish new Docker images based on Debian 8.

Learn more about the Bitnami tagging policy and the difference between rolling tags and immutable tags [in our documentation page](https://docs.bitnami.com/containers/how-to/understand-rolling-tags-containers/).


* [`0-ol-7`, `0.1.30-ol-7-r9` (0/ol-7/Dockerfile)](https://github.com/bitnami/bitnami-docker-user-broker/blob/0.1.30-ol-7-r9/0/ol-7/Dockerfile)
* [`0-debian-9`, `0.1.30-debian-9-r8`, `0`, `0.1.30`, `0.1.30-r8`, `latest` (0/debian-9/Dockerfile)](https://github.com/bitnami/bitnami-docker-user-broker/blob/0.1.30-debian-9-r8/0/debian-9/Dockerfile)

Subscribe to project updates by watching the [bitnami/user-broker GitHub repo](https://github.com/bitnami/bitnami-docker-user-broker).

# Get this image

The recommended way to get the Bitnami Service-catalog Docker Image is to pull the prebuilt image from the [Docker Hub Registry](https://hub.docker.com/r/bitnami/user-broker).

```bash
$ docker pull bitnami/user-broker:latest
```

To use a specific version, you can pull a versioned tag. You can view the [list of available versions](https://hub.docker.com/r/bitnami/user-broker/tags/) in the Docker Hub Registry.

```bash
$ docker pull bitnami/user-broker:[TAG]
```

If you wish, you can also build the image yourself.

```bash
$ docker build -t bitnami/user-broker:latest https://github.com/bitnami/bitnami-docker-user-broker.git
```

# Configuration

## Further documentation

For further documentation, please check [Service Catalog documentation](https://kubernetes.io/docs/concepts/extend-kubernetes/service-catalog/)

# Contributing

We'd love for you to contribute to this container. You can request new features by creating an [issue](https://github.com/bitnami/bitnami-docker-user-broker/issues), or submit a [pull request](https://github.com/bitnami/bitnami-docker-user-broker/pulls) with your contribution.

# Issues

If you encountered a problem running this container, you can file an [issue](https://github.com/bitnami/bitnami-docker-user-broker/issues). For us to provide better support, be sure to include the following information in your issue:

- Host OS and version
- Docker version (`docker version`)
- Output of `docker info`
- Version of this container
- The command you used to run the container, and any relevant output you saw (masking any sensitive information)

# License

Copyright 2018 Bitnami

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
