# Flannel Ansible Role

Configures flannel for a Kubernetes cluster.

## Configuration

| Key                       | Description                                                                                                    |
| ------------------------- | -------------------------------------------------------------------------------------------------------------- |
| `flannel_version`         | The version of flannel to be installed.                                                                        |
| `flannel_docker_registry` | The docker registry used to pull the flannel image.                                                            |
| `flannel_iface`           | The network interface used for flannel. Defaults to the Ansible default as described by the default_ipv4 fact. |
| `kube_pod_cidr_range`     | The pod IP range the cluster has been configured to use.                                                       |
