#
This is basic setup o k8s cluster with http server (nginx service)

HOW-TO:
Before you start map your docker ip address to k3s.local domain in `/etc/hosts` (in linux and macos) and `%SystemRoot%\system32\drivers\etc\hosts` (in Windows)

```
1. kubectl create -f deployment.yml
2. kubectl create -f service.yml
3. kubectl create -f middleware.yml
4. kubectl create -f ingress.yml
```

Service is exposed to internal `31313` port, so service should be reachable by accessing http://k3s.local:31313