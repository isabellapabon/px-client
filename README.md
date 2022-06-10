# px-client

Allows Kubernetes nodes to provide volumes to a cluster without having to join a Portworx cluster.

px-client is a CSI driver that will provide volumes to a client Kubernetes cluster that does not need to join a Portworx storage cluster. It does this by communicating with the storage cluster over gRPC and mounting volumes over NFS.

