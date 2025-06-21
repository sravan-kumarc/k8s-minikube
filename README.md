# k8s-minikube
#k8s-minikube


Imperative Commands:
---

kubectl create namespace blue --dry-run=client -o yaml >blue_namespace.yaml

kubectl run zinc-pod --image=nginx --port=80 --dry-run=client -o yaml >zinc-pod.yaml
