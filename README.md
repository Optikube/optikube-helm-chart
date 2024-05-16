# OptiKube Helm Chart
This is the official Helm chart for OptiKube, an open-source tool to optimize and manage Kubernetes resources. Please see the [organization page](https://github.com/Optikube) for more details on what OptiKube can do for you or contact optikube@gmail.com for assistance.

## Version Support
| Chart Version | Kubernetes Min | Kubernetes Max |
|---------------|----------------|----------------|
| 1.0.1         | 1.20           | 1.30           |

## Installation
To install via Helm, run the following command in your terminal.
```
helm repo add optikube https://optikube.github.io/optikube-helm-chart/ && \
helm repo update && \
helm install optikube optikube/optikube --namespace optikube --create-namespace
```
## Updating OptiKube
To update your current version of OptiKube via Helm, run the following command in your terminal.
```
helm repo add optikube https://optikube.github.io/optikube-helm-chart/ && \
helm repo update && \
helm upgrade optikube optikube/optikube -n optikube
```
## Deleting OptiKube
To remove remove OptiKube from your cluster via Helm, run the following command in your terminal.
  ```
helm uninstall optikube -n optikube
  ```
