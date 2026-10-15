#product secrets 
STORAGE_PATH=postgres://
kubectl -n shop create secret generic product-service-secret --from-file=.env=product.env
