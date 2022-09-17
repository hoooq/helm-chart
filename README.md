# helm-chart

## To Build and `pump version`, create a new branch with version. Example: 

```bash
git checkout -b 0.1.5
```

## Add repository

```sh
helm repo add hoooq https://hoooq.github.io/helm-chart
```


## Install

```sh
helm install my-hoooq hoooq/hoooq-charts
```


# Development

## Pull Request branch

Example: `0.1.22`
Command:
```sh
git checkout -b 0.1.22
```

## Local generate

```sh
helm template . | less
```
