# istesdns.de

## About

Source of <https://istesdns.de> which is the german version of <https://isitdns.com>. Both sites give you the answer to
that buring question you had when you encountered issues with your network.

## Kubernetes

I also created a deployable version of this as k8s manifests, see the `k8s` directory. The configuration to expose this
via a cloudflare tunnel (rackspace's loadbalancer service is just too damn expensive!) is in a
[separate](https://github.com/Alestrix/cloudflare-k8s) repo.
