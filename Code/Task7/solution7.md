## Type Commands in Shell

---

- # <b>Solution</b>

- ## `kubectl get rs`
- ## `vi replicaset.yaml`
- ## Paste replicaset.yaml
- ## `kubectl apply -f replicaset.yaml`
- ## `kubectl get rs`

---

### References:

1. https://kubernetes.io/docs/concepts/workloads/controllers/replicaset/#example

### Why need ReplicaSet if Deployment has replicas attribute;
### Difference between ReplicaSet and Deployment

```
A Kubernetes Deployment:
1. higher-level object that manages ReplicaSets,
2. declarative updates, rolling updates/rollbacks scaling
3. ensure specific number of identical Pods are always running,
4. deployments orchestrate ReplicaSets to handle application lifecycles
whereas ReplicaSets just maintain pod availability. 

ReplicaSet
1. low level controller
2. guarantees stable set of replica Pods are running at any given time.
3. scales Pods up or down, creates new Pods if they crash.
4. manage different application versions.
Limitations: Lacks built-in features for rolling updates, rollbacks, or 

Deployment
Purpose: Manages ReplicaSets to control the deployment, update, and rollback of application versions.
Functionality:
Rolling Updates: Gradually replaces old Pods with new ones, allowing for zero downtime.
Rollbacks: Easily revert to a previous stable version if an update fails.
Scaling: Manages the desired number of replicas.
Declarative Updates: Defines the desired state, and the controller moves the current state to match it.
Usage: The standard way to manage stateless applications; it automatically creates and manages ReplicaSets. 

When to Use Which
Always use a Deployment for managing applications, as it abstracts away the need to manually manage ReplicaSets and provides essential features for modern application lifecycle management.
Use a ReplicaSet directly only in very specific, advanced scenarios where you need fine-grained control over pod replication without the update/rollback features of a Deployment, or for simple tasks like scaling existing Pods. 

```



Labels 'type' is not set to 'front-end'

