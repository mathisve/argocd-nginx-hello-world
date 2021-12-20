# argocd-nginx-hello-world
first argocd test, please ignore

a small sample application to test argocd

when deploying in minikube, don't forget to change `/etc/hosts` to include 

```localhost   nginx.test```

once deployed do:

```curl nginx.test:8080```