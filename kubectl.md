# kubectl

Various handy examples of using `kubectl`.

## kubectl top

Insights into the resources usage for a node or a pod.

```
# get resource consumption for all nodes
kubectl top node

# get resource consumption for a specific node
kubectl top node nodename

# get resource consumption for nodes that match a label
kubectl top node -l key=value

# get resource consumption for all pods
kubectl top pods

# get resource consumption for a specific pod
kubectl top pods podname

# get resource consumption for pods that match a label
kubectl top pods -l key=value

# get resource consumption for all pods split by container
kubectl top pods --containers
```
