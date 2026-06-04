## Type Commands in Shell

---

- # <b>Solution</b>

- ## `kubectl get deployment`
- ## `kubectl get svc`
- ## `kubectl set image deployment/nginx-deployment nginx-container=nginx:latest`
- ## `kubectl scale deployment/nginx-deployment --replicas=5`
- ## `kubectl edit svc/nginx-service`

```
Change nodeport to 32165

```
- ## congratulations..

---

### References:

1. https://kubernetes.io/docs/concepts/workloads/controllers/deployment/#scaling-a-deployment

2. https://kubernetes.io/docs/concepts/workloads/controllers/deployment/#updating-a-deployment

3. https://kubernetes.io/docs/reference/kubectl/generated/kubectl_edit/#examples