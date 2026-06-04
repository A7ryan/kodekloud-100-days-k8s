- ## `kubectl  describe deployments.apps redis-deployment-t4q2`

```
(Error: spell mistake)
Image name is:
    redis:alpin

I should be:
    redis:alpine
```

- ## `kubectl set image deployment/redis-deployment-t4q2 redis-container=redis:alpine`

- ## `kubectl edit deployment `

```
it was wrong configmap name earlier: redis-config-t4q2


ConfigMap:
          defaultMode: 420
          name: redis-config-t4q2

```