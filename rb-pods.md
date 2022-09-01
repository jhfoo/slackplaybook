### My test runbook
texts here will not be parsed

#### pod list <namespace> [<cluster>|all]
Lists pods in real time in a given namespace-cluster. When only namespace provided all clusters will be scanned.

Similar to
```
kubectl x y z
```

#### pod delete <namespace> <cluster>
Deletes pods matching the namespace in the cluster. 'All' is accepted as ClusterId.
  
Similar to
```
kubectl delete pod x y z
```
