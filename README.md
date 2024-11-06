# k8s

## To run kube

1. open docker desktop
    1. Go to 'setting' at the top right
    2. Go to 'kubernetes' tab
    3. Click 'Enable Kubernetes'
2. go to '/manifests'
    1. run `kubectl apply -f .`
    2. run `kubectl get po` to check if all the pods are running
    3. to delete all `kubectl delete -f .` or `kubectl delete all --all`