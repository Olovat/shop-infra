#auth service secrets
STORAGE_PATH=postgres://
SECRET=
kubectl -n shop create secret generic auth-service-secret --from-file=.env=auth.env