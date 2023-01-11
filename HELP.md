### Para criar o namespace:
```
kubectl create -f namespaces/vote.yaml
```

### Para criar todos os deployments kubernetes executar:
```
kubectl create -f deployments/
```

### Para todos os services:
```
kubectl create -f services/
```

### Para saber onde o serviço está rodando
```
minikube service result --url -n vote
minikube service vote --url -n vote
```

### Para verificar os objetos criados 
```
kubectl get all -n vote
```