# k8s Sandbox CRD

The same controller pattern as a Deployment managing pods: the Sandbox adds lifecycle management around an ordinary pod. gVisor (or any other isolation primitive) will change how that pod runs, while the Sandbox remains the management object.

# Tests

- [x] Sandbox with dumb heartbeat container
