# netbox-docker

This is the repository for building OxCERT's customized netbox
container setup. This is applying local customizations to the
upstream docker image provided by [Netbox
Community](https://github.com/netbox-community/netbox-docker)

We take the upstream docker images and add various Netbox extension
modules, plus add any resulting configuration settings and any default
configuration settings we will always require. The idea is that using
our customized `netbox-docker` image will be simply a matter of pull
and run, with no additional configuration steps needed. This also has
the benefit that we are assured that all testing is being run against
the exact same image as will be used in production.

## Upstream docker image:

```
netboxcommunity/netbox:latest
```
