# helm-chart-values

Helm chart values I've customized and deployed.

## loki-stack

https://grafana.com/docs/loki/latest/installation/helm/

```sh
helm repo add grafana https://grafana.github.io/helm-charts
helm install loki-stack grafana/loki-stack --values loki-stack-values.yml -n loki --create-namespace
```

## metallb

```sh
helm repo add bitnami https://charts.bitnami.com/bitnami
helm install metallb bitnami/metallb -n metallb --create-namespace
```


## minecraft

```sh
helm repo add itzg https://itzg.github.io/minecraft-server-charts/
helm install minecraft itzg/minecraft -n minecraft --create-namespace --values minecraft-values.yml
```

## gitea

```sh
helm repo add gitea-charts https://dl.gitea.io/charts/
helm install gitea gitea-charts/gitea
```
