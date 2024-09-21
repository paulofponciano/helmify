![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)

# Helmify Labs

## Use

```sh
cat manifests/backstage.yaml | helmify charts/backstage
```

## Install

- Helm

```sh
wget https://get.helm.sh/helm-v3.16.1-linux-amd64.tar.gz
tar -zxvf helm-v3.16.1-linux-amd64.tar.gz
sudo mv linux-amd64/helm /usr/local/bin/helm
```

- Helmify

```sh
wget https://github.com/arttor/helmify/releases/download/v0.4.14/helmify_Linux_x86_64.tar.gz
tar -xvzf helmify_Linux_x86_64.tar.gz
sudo cp helmify /usr/bin/
helmify --version
```
---