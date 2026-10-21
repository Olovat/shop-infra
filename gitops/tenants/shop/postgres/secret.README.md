#POSTGREPASS
kubectl -n shop create secret generic postgres-secret --from-literal=POSTGRES_PASSWORD=YOUR_SECRET_PASS