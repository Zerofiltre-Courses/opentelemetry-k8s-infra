👉 [Repo](https://github.com/open-telemetry/opentelemetry-helm-charts)

👉 [Documentation](https://opentelemetry.io/docs/kubernetes/helm/collector/)

## Installation

```shell
 helm install otelcol open-telemetry/opentelemetry-collector -f values.yml -n namespace
```

## Upgrade

```shell
 helm upgrade otelcol open-telemetry/opentelemetry-collector -f values.yml -n namespace
```


## Deletion
```shell
helm un otelcol -n monitoring
```

