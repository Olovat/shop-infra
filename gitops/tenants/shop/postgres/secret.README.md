#POSTGREPASS
kubectl -n shop create secret generic password-secret --from-literal=POSTGRES_PASSWORD=YOUR_SECRET_PASS