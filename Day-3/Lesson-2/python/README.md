## Example Python Application using Kubernetes Client Library

### Tools
* Docker

### Build
 
**Docker image for inside the cluster usage:**
```
make docker-build
```

### Run

**Docker image for inside the cluster usage:**
```
make k8s-run
```

### Dependency Management
* [glide](https://github.com/Masterminds/glide) is used for vendoring and dependency management.
* If you need to change client library version, update `glide.yaml` file and run `glide up`. 