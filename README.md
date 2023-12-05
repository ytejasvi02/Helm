# Helm
Helm charts and description

It is a package manager for Kubernetes.

There are different commands in Helm like;

-helm create hello-world // create a directiry structure for helm chart with various templates and files.
-kubernetes resources like deployment.yaml and service.yaml
-helm install my-hello-world// released name will be my-hello-world
-kubectl get deployments// verifying deployments
-kubectl get services// verifying deployments 

Helm charts: helm create <chart name>// bundles the YAML files we created
              helm install <chart name>// to deploy the kubernetes application



Below are the steps to incorporate helm into DevOps pipeline:

1. Install Helm and configure it with kubernetes cluster
2. Create a Helm chart manually or by using "helm create"
3. Keep your source code in repository
4. Setup CI/CD pipeline and define workflow in YAML file
5. abc


