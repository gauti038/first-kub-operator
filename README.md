# first-kub-operator

## Deploy Steps

1. apply the simple-operator.yaml file to kubernetes
2. See a new deployment with operator code running and view its logs
3. apply the exchangerate.yaml file with CRD but see new configmaps getting created on the fly
4. If you delete exchangerate.yaml, the new configmaps are also deleted.
5. Uses kopf to write operators
