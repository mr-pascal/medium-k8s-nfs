# medium-k8s-nfs


```sh


### Apply all manifests
kubectl apply -f .

### Port forward port to web Service
kubectl port-forward svc/nfs-web 8080:80

```