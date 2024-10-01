### What is kubectl?

kubectl is a command-line tool used to manage Kubernetes clusters.

What Does It Do?

	•	Interact with Kubernetes clusters: You can manage both local (e.g., Minikube) and cloud-based (e.g., AWS, Azure, GCP) Kubernetes clusters.
	•	Application deployment: Easily deploy your containerized applications to Kubernetes clusters.
	•	Resource management: Create, update, or delete Kubernetes resources such as pods, deployments, and services.

For more detailed information about kubectl, you can refer to Kubernetes’ official documentation: [Overview of kubectl](https://kubernetes.io/docs/reference/kubectl/overview/) 

### kubectl cheat sheet

| Listing Resources        |                                            |
| ------------------------ | ------------------------------------------ |
| kubectl get nodes        | List all nodes in cluster                  |
| kubectl get namespaces   | List all namespaces in cluster             |
| kubectl get pods         | List all pods in default namespace cluster |
| kubectl get pods -n name | List all pods in the "name" namespace          |

| Creating Resources            |                                             |
| ----------------------------- | ------------------------------------------- |
| kubectl create namespace name | Create a namespace called "name"            |
| kubectl create -f [filename]  | Create a resource from a JSON or YAML file: |

| Editing Resources            |                   |
| ---------------------------- | ----------------- |
| kubectl edit svc/servicename | To edit a service |

| More detail on Resources |                                                         |
| ------------------------ | ------------------------------------------------------- |
| kubectl describe nodes   | display the state of any number of resources in detail, |

| Delete Resources   |                                                  |
| ------------------ | ------------------------------------------------ |
| kubectl delete pod | Remove resources, this can be from stdin or file |

| Short name | Full name                  |
| ---------- | -------------------------- |
| csr        | certificatesigningrequests |
| cs         | componentstatuses          |
| cm         | configmaps                 |
| ds         | daemonsets                 |
| deploy     | deployments                |
| ep         | endpoints                  |
| ev         | events                     |
| hpa        | horizontalpodautoscalers   |
| ing        | ingresses                  |
| limits     | limitranges                |
| ns         | namespaces                 |
| no         | nodes                      |
| pvc        | persistentvolumeclaims     |
| pv         | persistentvolumes          |
| po         | pods                       |
| pdb        | poddisruptionbudgets       |
| psp        | podsecuritypolicies        |
| rs         | replicasets                |
| rc         | replicationcontrollers     |
| quota      | resourcequotas             |
| sa         | serviceaccounts            |
| svc        | services                   |