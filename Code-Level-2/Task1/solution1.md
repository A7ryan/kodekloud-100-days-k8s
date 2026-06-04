## Type Commands in Shell

---

- # <b>Solution</b>

- ## check what is present currently
- ## `kubectl get all`

- ## `vi pod.yaml`
- ## Paste pod.yaml
- ## `kubectl apply -f pod.yaml`
- ## `kubectl get pods`

- ## `kubectl exec volume-share-devops -c volume-container-devops-1 -i -t -- bash -il`
- ## `cd /tmp/blog`

- ## Please install vi or nano as per your preference
- ## `vi blog.txt`

```
Paste:
Welcome to xFusionCorp Industries

```

- Check if share volume is working

- ## `kubectl exec volume-share-devops -c volume-container-devops-2 -i -t -- bash -il`
- ## `cd /tmp/cluster`
- ## `cat blog.txt`

- ## Congratulations...

---

### References:

1. https://kubernetes.io/docs/concepts/storage/volumes/#emptydir-memory-configuration-example
