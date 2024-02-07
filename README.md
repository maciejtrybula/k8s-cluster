#
This is basic setup o k8s cluster with http server (nginx service)

HOW-TO:

```
1. kubectl create -f deployment.yml
2. kubectl create -f service.yml
3. kubectl create -f middleware.yml
4. kubectl create -f ingress.yml