# Wakapi

A minimalist, self-hosted WakaTime-compatible backend for coding statistics

[Source Repository](https://github.com/muety/wakapi)

## Installation

```
helm repo add bibletoon-charts https://bibletoon.github.io/Charts/
helm repo update
helm install -f values.yml wakapi bibletoon-charts/wakapi
```

## Configuration

App configuration options can be found [in source repo](https://github.com/muety/wakapi#-configuration-options)

Default values can be found [there](./values.yaml)

*This chart is forked from [andreymaznyak](https://github.com/andreymaznyak/wakapi-helm-chart)*