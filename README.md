# k8s-minikube
#k8s-minikube


Imperative Commands:
---

kubectl create namespace blue --dry-run=client -o yaml >blue_namespace.yaml
![image](https://github.com/user-attachments/assets/84861a4c-fcaa-4012-8a41-894169dd45f4)



kubectl run zinc-pod --image=nginx --port=80 --dry-run=client -o yaml >zinc-pod.yaml
![image](https://github.com/user-attachments/assets/a1f62cb1-9dab-4789-a9e5-79b4e995dd4f)

