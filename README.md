# PERN Helm Chart

```sh
helm package .
```

```sh
helm repo index --url https://aldinkapetanovic.github.io/pern-helm .
```

```sh
helm repo add pern-helm https://aldinkapetanovic.github.io/pern-helm
```

```sh
helm install pern-app pern-helm/pern-helm -n pern --create-namespace
```