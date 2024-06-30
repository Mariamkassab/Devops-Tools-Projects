# keda (Kubernetes Event-driven Autoscaling)

! Make sure that you installed the matrix server on your K8s cluster.

## install KEDA to your cluster

```
helm repo add kedacore https://kedacore.github.io/charts
helm repo update
helm install keda kedacore/keda
```

## Install your Deployment & Scaledobject

```
git clone https://github.com/Mariamkassab/Devops-Tools-Projects.git
cd Devops-Tools-Projects/kEDA
kubectl apply -f .
```

