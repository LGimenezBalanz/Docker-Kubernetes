# Docker exercise 11


## run deployment
```
$ kubectl apply -f .\deployment.yaml
```

## verificar
```
$ kubectl get all
$ kubectl exec -it pod/passwordapi-b6f77cdf9-h5qrb (podname) -- bash 
# curl localhost:3000
```
