For deploying an environment congifuration toy can run:

kubectl kustomize overlays/prod | kubectl apply -f -


or

kubectl kustomize overlays/prod > tmp_prod.yaml
kubectl apply -f tmp_prod.yaml


https://kubernetes.io/docs/tasks/manage-kubernetes-objects/kustomization/