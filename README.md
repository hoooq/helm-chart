# helm-chart

## Add repository

```sh
helm repo add hoooq https://hoooq.github.io/helm-chart
```


## Install

```sh
helm install my-hoooq hoooq/hoooq-charts
```


# Development

## Package

```sh
helm package .
```

## Indexing

```sh
helm repo index --url https://hoooq.github.io/helm-chart .
```
