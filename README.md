
## k8s 테스트

### Deployment 생성

```shell
kubectl apply -f nginx-deployment.yaml
```

### Deployment 상태확인

```shell
kubectl get deployments
```

### Pod 목록 조회

```shell
kubectl get pods
```

### Pod 로그 확인

```shell
kubectl logs <pod-name>
```

### Pod 접속

```shell
kubectl exec -it <pod-name> -- /bin/bash
```

- [용어정리](./document/wiki_main.md)# testk8s
