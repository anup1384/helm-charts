This repository hosts [Helm](https://helm.sh) charts.

## Add Helm repository

```bash
helm repo add helm-charts  https://anup1384.github.io/helm-charts/
helm repo update
```
![image](https://user-images.githubusercontent.com/28804150/117174070-fc31b280-adea-11eb-9278-4b701eaf2008.png)

## Install chart

```bash
helm upgrade --install app helm-charts/application
```
