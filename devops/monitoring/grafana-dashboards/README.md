# grafana-dashboards

A Helm chart for Kubernetes

![Version: 0.1.11](https://img.shields.io/badge/Version-0.1.11-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 1.16.0](https://img.shields.io/badge/AppVersion-1.16.0-informational?style=flat-square)

## Installing the Chart

To install the chart with the release name `my-release`:

```console
$ helm install my-release chartmuseum/grafana-dashboards
```

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| labels | object | `{"grafana_dashboard":"true"}` | Label to assign to configmaps |
