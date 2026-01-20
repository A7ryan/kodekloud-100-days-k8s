## Type Commands in Shell

---

- # <b>Solution</b>

- ## `kubectl get pods`
- ## `kubectl get deployment`
- ## `kubectl describe deployment nginx-deployment`
- ## Note Container Name!!
- ## `kubectl set image deployments/nginx-deployment nginx-container=nginx:1.17`
- ## `kubectl rollout status deployments/nginx-deployment`

- ## Check your deployment status
- ## `kubectl describe deployment nginx-deployment`

---

### References:

1. https://kubernetes.io/docs/tutorials/kubernetes-basics/update/update-intro/

2. https://kubernetes.io/docs/concepts/workloads/controllers/deployment/