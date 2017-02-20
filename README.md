# [CHStudio](https://hub.docker.com/u/chstudio) Docker Images [![build status](https://gitlab.com/chstudio/docker-images/badges/master/build.svg)](https://gitlab.com/chstudio/docker-images/commits/master)

This repository contains Dockerfile that can be used in the CI pipelines on different projects.

## [chstudio/php-ci](https://hub.docker.com/r/chstudio/php-ci/)

A PHP version built and configured to be used in continuous integration pipelines.
It contains all the debugging tools required to run raw PHP : `composer`, `xdebug`, `git`.

## [chstudio/php-ci.mysql](https://hub.docker.com/r/chstudio/php-ci.mysql/)

An extension to the `php-ci` image with the tools necessary to check MySQL related code.
It contains MySQL command line tools and the MySQL PHP extension `pdo_mysql`, `mysqli`.

## Contributing

We welcome everyone to contribute to this project. Below are some of the things that you can do to contribute.

- Read [our contributing guide](CONTRIBUTING.md).
- [Fork us](https://gitlab.com/chstudio/docker-images/forks/new) and [request a merge](https://gitlab.com/chstudio/docker-images/merge_requests) to the [master](https://gitlab.com/chstudio/docker-images/tree/master) branch.
- Submit [bug reports or feature requests](https://gitlab.com/chstudio/docker-images/issues) to GitLab.

## Mirrors

The code in the repository is also mirrored on :

* [GitHub](https://github.com/chstudio/docker-images)
