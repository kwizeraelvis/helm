# Collabora Code Helm Charts
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/collabora-code-aos)](https://artifacthub.io/packages/search?repo=collabora-code-aos)
[Helm](https://helm.sh) repo for different charts related which can be installed on [Kubernetes](https://kubernetes.io)

### Add Helm repository

To add the repo just run:

```bash
helm repo add kwizeraelvis https://kwizeraelvis.github.io/helm/
helm repo update
```

### Helm Charts

* [collabora-code](https://kwizeraelvis.github.io/helm/)

  ```bash
  helm install my-release kwizeraelvis/collabora-code
  ```

