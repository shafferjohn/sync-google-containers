# Sync Google Containers

sync [google-containers](https://console.cloud.google.com/gcr/images/google-containers/GLOBAL)

docker hub: [https://hub.docker.com/u/syncgooglecontainers](https://hub.docker.com/u/syncgooglecontainers)

### Example
```bash
docker pull syncgooglecontainers/google-containers/kube-apiserver:v1.18.6
docker pull syncgooglecontainers/google-containers/kube-controller-manager:v1.18.6
docker pull syncgooglecontainers/google-containers/kube-scheduler:v1.18.6
docker pull syncgooglecontainers/google-containers/kube-proxy:v1.18.6
docker pull syncgooglecontainers/google-containers/pause:3.2
docker pull syncgooglecontainers/google-containers/etcd:3.4.3-0
docker pull syncgooglecontainers/google-containers/coredns:1.6.7

docker tag syncgooglecontainers/kube-apiserver:v1.18.6 k8s.gcr.io/kube-apiserver:v1.18.6
docker tag syncgooglecontainers/kube-controller-manager:v1.18.6 k8s.gcr.io/kube-controller-manager:v1.18.6
docker tag syncgooglecontainers/kube-scheduler:v1.18.6 k8s.gcr.io/kube-scheduler:v1.18.6
docker tag syncgooglecontainers/kube-proxy:v1.18.6 k8s.gcr.io/kube-proxy:v1.18.6
docker tag syncgooglecontainers/pause:3.2 k8s.gcr.io/pause:3.2
docker tag syncgooglecontainers/etcd:3.4.3-0 k8s.gcr.io/etcd:3.4.3-0
docker tag syncgooglecontainers/coredns:1.6.7 k8s.gcr.io/coredns:1.6.7
```
