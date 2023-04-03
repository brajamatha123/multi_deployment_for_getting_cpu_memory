create deployment.yaml in that file we have request and limits of cpu  and memory
create namespaces using  below command
kubectl create ns namespacename
kubectl apply -f deploymentname -n namespacename--->to deploy yaml file
kubectl get pods--> to know the pods are running in default ns
kubectl get pods -A ----> to know the all pods are running
kubectl get pods -n namespace ---> here we will get how many pods are running in that specific namespace
kubectl describe po podname/pod id -n namespace--->to describe specific pod
kubectl scale deployment <deployment-name> --replicas=0 ----> it will delete all pods and replicas also
kubectl get nodes----> to know the how many nodes are available
