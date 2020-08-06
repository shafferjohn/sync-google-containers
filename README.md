# mirror-gcr
gcr.io mirror registry

docker hub: [https://hub.docker.com/u/shafferjohn](https://hub.docker.com/u/shafferjohn)

### Example
```bash
docker pull shafferjohn/kube-apiserver:v1.18.6
docker pull shafferjohn/kube-controller-manager:v1.18.6
docker pull shafferjohn/kube-scheduler:v1.18.6
docker pull shafferjohn/kube-proxy:v1.18.6
docker pull shafferjohn/pause:3.2
docker pull shafferjohn/etcd:3.4.3-0
docker pull shafferjohn/coredns:1.6.7

docker tag shafferjohn/kube-apiserver:v1.18.6 k8s.gcr.io/kube-apiserver:v1.18.6
docker tag shafferjohn/kube-controller-manager:v1.18.6 k8s.gcr.io/kube-controller-manager:v1.18.6
docker tag shafferjohn/kube-scheduler:v1.18.6 k8s.gcr.io/kube-scheduler:v1.18.6
docker tag shafferjohn/kube-proxy:v1.18.6 k8s.gcr.io/kube-proxy:v1.18.6
docker tag shafferjohn/pause:3.2 k8s.gcr.io/pause:3.2
docker tag shafferjohn/etcd:3.4.3-0 k8s.gcr.io/etcd:3.4.3-0
docker tag shafferjohn/coredns:1.6.7 k8s.gcr.io/coredns:1.6.7
```
