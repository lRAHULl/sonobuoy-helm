# Sonobuoy Helm Chart

> :warning: **This project is in development phase. Please do not use it in production environments.**

* Creates a CronJob which runs sonobuoy conformance tests against the given Kubernetes Cluster.
* Creates a Http file server and an optional grafana dashboard that visualizes the results of the tests.

[Sonobuoy](https://sonobuoy.io/) is a diagnostic tool that makes it easier to understand the state of a Kubernetes cluster by running a choice of configuration tests in an accessible and non-destructive manner.

## Installing the Chart

To install the chart with the release name `my-release`:

```console
helm install my-release ./
```

## Uninstalling the Chart

To uninstall/delete the my-release deployment:

```console
helm delete my-release
```
