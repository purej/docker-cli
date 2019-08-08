# Docker CLI Tools for Windows
Contains Docker CLI .exe tools for Windows as does tools are unfortunately not downloadable with a direct link - A full Docker-for-Windows installation is currently required, which is just too much if only the CLI tools are required (for example if running the docker-deamon inside a Minikube VM).

Download the required versions, remove the version number and put them somewhere in your PATH.

## Other CLI Tools
Other required tools for container-based development on Windows can be downloaded directly:

Kubectl for Windows - Use this download link (replace version)
https://storage.googleapis.com/kubernetes-release/release/v1.15.0/bin/windows/amd64/kubectl.exe

[Minkube for Windows](https://github.com/kubernetes/minikube/releases)

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

