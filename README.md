kubectl create namespace postgresql
kubectl apply -f pv-volume.yaml
kubectl apply -f pv-claim.yaml
kubectl apply -f postgres-secrets.yml
kubectl apply -f postgresql-server-deployment.yaml
kubectl apply -f postgres-service.yml
kubectl apply -f postgres-client.yml
