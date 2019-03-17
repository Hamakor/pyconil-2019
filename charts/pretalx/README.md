# pretalx

[pretalx](https://pretalx.org) is a Conference planning tool: CfP, scheduling, speaker management.

## Introduction

This chart bootstraps a pretalx deployment on a [Kubernetes](http://kubernetes.io) cluster using the [Helm](https://helm.sh) package manager.

TODO: fill in stuff (copy style from other charts?)

## Prerequisites

## Installing the Chart

To install the chart with the release name `my-release`:

```bash
$ helm install --name my-release pretalx_chart_path
```
TODO: fill in more details

> **Tip**: List all releases using `helm list`

## Uninstalling the Chart

To uninstall/delete the `my-release` deployment:

```bash
$ helm delete my-release
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

## Configuration

The following table lists the configurable parameters of the MySQL chart and their default values.

| Parameter                                    | Description                                                                                  | Default                                              |
| -------------------------------------------- | -------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| `image.repository`                           | `pretalx` image repository.                                                                    | `amitar/pretalx`                                   |

TODO: explain

Specify each parameter using the `--set key=value[,key=value]` argument to `helm install`. For example,

```bash
$ helm install --name my-release \
  --set var2=value1,var2=value2 \
    pretalx_chart_path
```

TODO: explain

Alternatively, a YAML file that specifies the values for the parameters can be provided while installing the chart. For example,

```bash
$ helm install --name my-release -f values.yaml pretalx_chart_path
```

> **Tip**: You can use the default [values.yaml](values.yaml)

## More details
