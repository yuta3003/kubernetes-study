
# Command List

- ノードの情報を取得
```
kubectl get nodes
```

- podの情報を取得
```
kubectl get pod
```

- pod削除
```
kubectl delete pod <pod name>
```

- デプロイメントを作成
```
kubectl apply -f nginx.yaml
```

- デプロイメントを作成
```
kubectl run --image=nginx --port=80 nginx
```

- サービスの作成
```
kubectl expose deployment nginx --port=80 --type=NodePort
```

- minikube内dockerを使用する
```
eval $(minikube docker-env)
```

- dashboard表示
```
minikube dashboard
```
