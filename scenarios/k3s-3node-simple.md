# Setup a 3-node simple app cluster

1. Setup k3s server on the master server

```bash
curl -sfL https://get.k3s.io | sh -
#then check if its has been setup correctly with these commands:
k3s kubectl cluster-info
k3s kubectl get ndoes
```

2. get node-token from master node server...

3. Setup k3s agent on worker nodes and add them to master
