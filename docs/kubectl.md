#Kubectl

## Shell

Connect to a pod using bash

```bash
kubectl exec -n $NAMESPACE --stdin --tty $PODNAME -- /bin/bash
```