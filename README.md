# Docker / Kubernetes CLI Tools for Windows
This repo contains or links several CLI (.exe) tools for Windows 10, which are required to develop cloud/container-based applications using [Docker](https://www.docker.com/) and [Kubernetes](https://kubernetes.io/).

If you are using a full-blown [Docker-for-Windows](https://hub.docker.com/editions/community/docker-ce-desktop-windows) installation, those CLI tools are already available, so this isn't for you. But if you want to use a lightweight setup without a full Docker-for-Windows installation (for example using the docker-deamon from a local Minikube VM or another remote docker-deamon), just download the CLIs into any directory, put it into your path and your ready to go!

Where possible, the required tools are linked from there original source. But some tools do not provide a direct download link so are provided here for convenience.

### Docker CLI

| Docker-for-Windows | All CLIs | docker.exe | docker-compose.exe |
| ---- | --- | --- | --- | --- |
| 2.2.0.3 (2020-02-11) | [2.2.0.3](https://github.com/purej/docker-windows-cli/raw/master/docker-for-windows-2.2.0.3/docker-cli-2.2.0.3.zip) | [19.03.5](https://github.com/purej/docker-windows-cli/raw/master/docker-for-windows-2.2.0.3/docker.exe) | [1.25.4](https://github.com/docker/compose/releases/tag/1.25.4) |
| 2.1.0.5 (2019-11-18) | [2.1.0.5](https://github.com/purej/docker-windows-cli/raw/master/docker-for-windows-2.1.0.5/docker-cli-2.1.0.5.zip) | [19.03.5](https://github.com/purej/docker-windows-cli/raw/master/docker-for-windows-2.1.0.5/docker.exe) | [1.24.1](https://github.com/docker/compose/releases/tag/1.24.1) |
| 2.1.0.4 (2019-10-21) | [2.1.0.4](https://github.com/purej/docker-windows-cli/raw/master/docker-for-windows-2.1.0.4/docker-cli-2.1.0.4.zip) | [19.03.4](https://github.com/purej/docker-windows-cli/raw/master/docker-for-windows-2.1.0.4/docker.exe) | [1.24.1](https://github.com/docker/compose/releases/tag/1.24.1) |
| 2.1.0.2 (2019-09-04) | [2.1.0.2](https://github.com/purej/docker-windows-cli/raw/master/docker-for-windows-2.1.0.2/docker-cli-2.1.0.2.zip) | [19.03.2](https://github.com/purej/docker-windows-cli/raw/master/docker-for-windows-2.1.0.2/docker.exe) | [1.24.1](https://github.com/docker/compose/releases/tag/1.24.1) |
| 2.1.0.0 (2019-08-01) | [2.1.0.0](https://github.com/purej/docker-windows-cli/raw/master/docker-for-windows-2.1.0.0/docker-cli-2.1.0.0.zip) | [19.03.1](https://github.com/purej/docker-windows-cli/raw/master/docker-for-windows-2.1.0.0/docker.exe) | [1.24.1](https://github.com/docker/compose/releases/tag/1.24.1) |
| 2.0.0.2 (2019-01-16) | [2.0.0.2](https://github.com/purej/docker-windows-cli/raw/master/docker-for-windows-2.0.0.2/docker-cli-2.0.0.2.zip) | [18.09.1](https://github.com/purej/docker-windows-cli/raw/master/docker-for-windows-2.0.0.2/docker.exe) | [1.23.2](https://github.com/docker/compose/releases/tag/1.23.2) |


See [all releases](https://docs.docker.com/docker-for-windows/release-notes/)

### Kubernetes CLI
| Kubernetes | kubectl.exe |
| ---- | --- |
| 1.15.2 (2019-08-05) | [v1.15.2](https://storage.googleapis.com/kubernetes-release/release/v1.15.2/bin/windows/amd64/kubectl.exe) |
| 1.15.0 (2019-06-19) | [v1.15.0](https://storage.googleapis.com/kubernetes-release/release/v1.15.0/bin/windows/amd64/kubectl.exe) |
| 1.14.6 (2019-08-19) | [v1.14.6](https://storage.googleapis.com/kubernetes-release/release/v1.14.6/bin/windows/amd64/kubectl.exe) |
| 1.14.3 (2019-06-06) | [v1.14.3](https://storage.googleapis.com/kubernetes-release/release/v1.14.3/bin/windows/amd64/kubectl.exe) |

See [all releases](https://github.com/kubernetes/kubernetes/releases)

### Minikube CLI
| Minikube | minikube.exe | Server-Side Kubernetes / Docker-Deamon |
| ---- | --- | --- |
| [1.5.2](https://github.com/kubernetes/minikube/releases/tag/v1.5.2) (2019-10-31) | [1.5.2](https://github.com/kubernetes/minikube/releases/download/v1.5.2/minikube-windows-amd64.exe) | v1.16.2 / 18.09.9 |
| [1.4.0](https://github.com/kubernetes/minikube/releases/tag/v1.4.0) (2019-09-17) | [1.4.0](https://github.com/kubernetes/minikube/releases/download/v1.4.0/minikube-windows-amd64.exe) | v1.16.0 / 18.09.9 |
| [1.3.0](https://github.com/kubernetes/minikube/releases/tag/v1.3.0) (2019-08-06) | [1.3.0](https://github.com/kubernetes/minikube/releases/download/v1.3.0/minikube-windows-amd64.exe) | v1.15.2 / 18.09.8 |
| [1.2.0](https://github.com/kubernetes/minikube/releases/tag/v1.2.0) (2019-06-24) | [1.2.0](https://github.com/kubernetes/minikube/releases/download/v1.2.0/minikube-windows-amd64.exe) | v1.15.0 / 18.09.6 |
| [1.1.1](https://github.com/kubernetes/minikube/releases/tag/v1.1.1) (2019-06-07) | [1.1.1](https://github.com/kubernetes/minikube/releases/download/v1.1.1/minikube-windows-amd64.exe) | v1.14.3 / 18.09.6  |

See [all releases](https://github.com/kubernetes/minikube/releases)

### Helm CLI
Download [Helm for Windows](https://github.com/helm/helm/releases)

