# Cranecloud helm chart

This is the helm chart for the cranecloud project. It is a collection of microservices that are used to manage and monitor cranes.

### Add the Cranecloud Helm repository

Before you can install the chart, you need to add the Cranecloud Helm repository to your Helm client.

```bash
helm repo add cranecloud https://cranecloud.github.io/helm-charts
```

### Installing the Chart

To install the chart with the release name `my-release`:

```bash
helm install --name my-release cranecloud/cranecloud
```

The command deploys the cranecloud chart on the Kubernetes cluster in the default configuration.
