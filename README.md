# helm-chart-values

Helm chart values I've customized and deployed.


## loki

```sh
helm install loki-stack grafana/loki-stack --values loki-stack-values.yml -n loki --create-namespace
```
