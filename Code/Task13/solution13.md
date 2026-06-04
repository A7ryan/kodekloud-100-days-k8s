## Type Commands in Shell


---

- ## Tasks

- ## ReplicationController - nginx image latest tag
- ## name: nginx-replicationcontroller
- ## labels app as nginx_app, and type as front-end. 
- ## container: nginx-container and set the replica count to 3.


---

- # <b>Solution</b>

- ## `vi replicaController.yaml`
- ## `paste replicaController.yaml`
- ## `kubectl apply -f replicaController.yaml`


---

### References:

1. https://kubernetes.io/docs/concepts/workloads/controllers/replicationcontroller/#running-an-example-replicationcontroller
