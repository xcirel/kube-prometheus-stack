# Kube Prometheus Stack

The Kube Prometheus Stack provides a set of manifests to help you get from 0 to Grafana dashboards for Kubernetes in a matter of minutes.

## Creating the App in ArgoCD

```bash
argocd app create -f app-staging.yaml
```

To get default values from Helm Chart for  customizations, run the following command:

```bash
helm show values prometheus-community/kube-prometheus-stack > values.yaml
```