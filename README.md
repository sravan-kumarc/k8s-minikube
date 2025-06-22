# k8s-minikube
#k8s-minikube


Imperative Commands:
---

kubectl create namespace blue --dry-run=client -o yaml >blue_namespace.yaml
![image](https://github.com/user-attachments/assets/4d3f1759-12d0-4b07-90e2-c0da852e09d3)


kubectl run zinc-pod --image=nginx --port=80 --dry-run=client -o yaml >zinc-pod.yaml
