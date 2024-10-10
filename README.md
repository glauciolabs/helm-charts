![Helm Chart](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=Helm&labelColor=0F1689)

## Custom Helm Chart Collection

### Chart Installation

To install the Helm chart, use the following command:

```bash
$ helm install --create-namespace --namespace <namespace> <app-name> app-chart/app-chart -f values.yaml
#### Install Generic k8s apps
```


### Installing Generic Kubernetes Apps


**[values.yaml](charts/app-chart/values.yaml)**

```bash
helm repo add app-chart https://glauciolabs.github.io/app-chart -f values.yaml
```
