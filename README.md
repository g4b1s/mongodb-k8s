## Install Standalone version of Mongodb on Kubernetes cluster

1) Apply as below

```shell
kubectl apply -f secrets.yaml
kubectl apply -f statefulsets.yaml
kubectl apply -f service.yaml
```

Use following to connect running mongodb

IP:27017

use admin
db.auth('user','30t1c4')