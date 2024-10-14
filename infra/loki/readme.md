👉🏼 [Repository]()

- Add chart :
```shell
helm repo add grafana https://grafana.github.io/helm-charts
```

- Install
```shell
helm install -f values.yaml loki grafana/loki -n monitoring
```


- Upgrade
```shell
helm ugrade -f values.yaml loki grafana/loki -n monitoring
```