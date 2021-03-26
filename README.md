Jay Soni

Kubernetes
Create a Kubernetes cluster using any method you'd like
Create a new namespace called staging.


Single Pod
Create a new pod called hello in this staging namespace, make sure it is in a healthy state. Use the hello image.


Multi-node
Assume you are operating a 3 node (node-1, node-2, and node-3) cluster, deploy a pod called p2 in every node of your cluster.


Multi-container Pod
Create a new pod called p3 in the staging namespace. This pod contains two containers and the pod only should be created when one of these two containers has a file called /app/ready.txt. The pod should fail if that container does not have that file.


Monitoring
Deploy prometheus alert manager and grafana into the kube-system namespace and configure customised alerts which is only going to be trigger when a pod has 80% of the CPU running for 60 seconds.
Deploy an ingress controller to protect prometheus and alert manager using any authentication method you'd like.