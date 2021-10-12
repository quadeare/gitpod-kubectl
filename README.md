# Gitpod Kubectl Workspace

## Introduction

Ready to use Gitpod Kubectl workspace with usefull plugins.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://gitlab.com/quadeare/gitpod-kubectl.git)

## How to use

Gitpod allow you to change default startup image by using `.gitpod.yml` file.

Simply add the following content :

```bash
image: quadeare/gitpod-kubectl:latest

```

## Base Image

``` dockerfile
FROM gitpod/workspace-base:latest
```

## Kubectl plugins

Installed plugin manager : `krew`

Plugins list : 

- neat 
- access-matrix
- advise-psp
- cert-manager
- ca-cert
- get-all
- ingress-nginx


