# Open-telemetry observability pipeline using Fluent Bit

This repository contains a sample configuration for Fluent Bit that can be used to send logs to [OpenTelemetry Collector] and metrics to [OpenTelemetry Collector].

## Prerequisites

- [Docker]
- [Docker Compose]
- [kubectl]

## How to install on Kubernetes cluster

```shell
$ cd collector
$ kubectl apply -f ./otel-collector-daemonset.yaml
```



#