# Docker / Kubernetes CLI Tools for Windows
This repo contains or links several CLI (.exe) tools for Windows 10, which are required to develop cloud/container-based applications using [Docker](https://www.docker.com/) and [Kubernetes](https://kubernetes.io/).

If you are using a full-blown [Docker-for-Windows](https://hub.docker.com/editions/community/docker-ce-desktop-windows) installation, those CLI tools are already available, so this isn't for you. But if you want to use a lightweight setup without a full Docker-for-Windows installation (for example using the docker-deamon from a local Minikube VM or another remote docker-deamon), just download the CLIs into any directory, put it into your path and your ready to go!

Where possible, the required tools are linked from there original source. But some tools do not provide a direct download link so are provided here for convenience.

### Docker CLI

| Docker-for-Windows | Docker | Docker-Compose | Docker-Machine |
| ---- | --- | --- | --- |
| 2.1.0.0 (2019-08-01) | 19.03.1 | [1.24.1](https://github.com/docker/compose/releases/tag/1.24.1) | [0.16.1](https://github.com/docker/machine/releases/tag/v0.16.0) |
| 2.0.0.2 (2019-01-16) | 18.09.1 | [1.23.2](https://github.com/docker/compose/releases/tag/1.23.2) | [0.16.1](https://github.com/docker/machine/releases/tag/v0.16.0) |

### Kubernetes CLI
| Kubernetes | kubectl |
| ---- | --- |
| 1.14.3 (2019-06-06) | [v1.14.3](https://storage.googleapis.com/kubernetes-release/release/v1.14.3/bin/windows/amd64/kubectl.exe) |

### Minikube CLI
| Minikube | Kubernetes (server-side) |
| ---- | --- |
| [1.3.0](https://github.com/kubernetes/minikube/releases/tag/v1.3.0) (2019-08-06) | ... |
| [1.2.0](https://github.com/kubernetes/minikube/releases/tag/v1.2.0) (2019-06-24) | ... |
| [1.1.1](https://github.com/kubernetes/minikube/releases/tag/v1.1.1) (2019-06-07) | v1.14.3 |



[Helm for Windows](https://github.com/helm/helm/releases)

## Versions
The folder contains the version numbers as used by Docker for Windows, see [Release Notes](https://docs.docker.com/docker-for-windows/release-notes/)

### 2.1.0.0 (2019-08-01)
Docker: 19.03.1
Compose: 1.24.1
Kubectl: v1.14.3
Notary: 0.6.1
Credential Helpers: 0.6.3
Machine: 0.16.1

### 2.0.0.2 (2019-01-16)
Docker: 18.09.1
Compose: 1.23.2
Kubectl: v1.10.11
Notary: 0.6.1
Credential Helpers: 0.6.0
Machine: 0.16.1

