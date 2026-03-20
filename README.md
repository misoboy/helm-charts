# helm-charts

> Personal Helm chart repository hosted on **GitHub Pages** — charts for various Kubernetes applications.

[![Helm](https://img.shields.io/badge/Helm-3.x-0F1689?logo=helm&logoColor=white)](https://helm.sh)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-ready-326CE5?logo=kubernetes&logoColor=white)](https://kubernetes.io)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue)](https://opensource.org/licenses/Apache-2.0)

## Usage

[Helm](https://helm.sh) must be installed to use the charts. Refer to Helm's [documentation](https://helm.sh/docs/) to get started.

### Add this Repository

```bash
helm repo add misoboy https://misoboy.github.io/helm-charts
helm repo update
```

### Search Available Charts

```bash
helm search repo misoboy
```

### Install a Chart

```bash
helm install my-release misoboy/<chart-name>
```

## Charts

| Chart | Description |
|-------|-------------|
| See `charts/` directory | Browse available charts |

## Contributing

To add or update a chart:

1. Create/update your chart in `charts/<chart-name>/`
2. Update `Chart.yaml` with the new version
3. Run `helm package charts/<chart-name>`
4. Run `helm repo index .`
5. Submit a PR

## License

[Apache 2.0](LICENSE)
