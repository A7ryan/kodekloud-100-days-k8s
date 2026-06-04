## Type Commands in Shell


---

- ## Tasks

- ## pod name is nginx-phpfpm
- ## configmap name is nginx-config
- ## copy /home/thor/index.php file from the jump host to the nginx-container
- ## container: nginx-container and set the replica count to 3.


---

- # <b>Solution</b>

- ## `kubectl describe pod nginx-phpfpm`

- ## `kubectl describe configmaps nginx-config`

- ## `kubectl cp /home/thor/index.php nginx-phpfpm:/usr/share/nginx/html`

- ## `kubectl edit configmaps nginx-config`

```
        # Set nginx to serve files from the shared volume!
        root /usr/share/nginx/html;
```

- ## `kubectl cp /home/thor/index.php nginx-phpfpm:/var/www/html`

---

### References:

1. https://kubernetes.io/docs/reference/kubectl/generated/kubectl_cp/

2. https://nginx.org/en/docs/beginners_guide.html