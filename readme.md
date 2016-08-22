# Dockport
Docker Management for SignalOS based on [Shipyard](https://github.com/shipyard/shipyard)

[![Build Status](https://travis-ci.org/norsig/dockport.svg?branch=master)](https://travis-ci.org/norsig/dockport)

This is very much a work in progress... For production ready code, use [Shipyard](https://github.com/shipyard/shipyard)

# Quick Start
There is a deploy script provided on the Northern Signal website for quick
installation.

> Note: you must already have a Docker engine available.  If you do not have
Docker, you can use [Docker Machine](https://github.com/docker/machine) to
get started.

```
curl -s https://northernsignal.com/deploy | bash -s
```
or if you are using SignalOS:
```
curl -s https://northernsignal.com/deploy | ash -s
```


For full options:

```
curl -s https://northernsignal.com.com/deploy | bash -s -- -h
```
