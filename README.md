This repository hosts OpenDevopsAutomation [Helm](https://helm.sh) charts.

## Add Helm repository

```bash
helm repo add opendevopsautomation https://opendevopsautomation.github.io/helm-charts/
helm repo update
```


## Install chart

```bash
helm upgrade --install app opendevopsautomation/application
```
