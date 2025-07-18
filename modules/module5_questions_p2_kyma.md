## Module 5 questions. Developing Applications in SAP BTP, Kyma Runtime
## Discovering Kyma
## Working with k8s workloads
---

### 1. Which of the following is TRUE about the relationship between Kyma and Kubernetes?
- **A)** Kyma is a standalone platform that does not require Kubernetes
- **B)** Kyma is built on top of Kubernetes and uses its extensibility features
- **C)** Kyma replaces the Kubernetes scheduler
- **D)** Kyma is only available as a managed service

**Answer:**  
> **B) Kyma is built on top of Kubernetes and uses its extensibility features**

---

### 2. What is a key difference between Open-Source Kyma and SAP BTP, Kyma Runtime?
- **A)** Open-Source Kyma is only available as a managed service
- **B)** SAP BTP, Kyma Runtime does not support Kyma modules
- **C)** SAP BTP, Kyma Runtime is a managed service with SLAs and a hosted dashboard, while Open-Source Kyma requires self-management
- **D)** Open-Source Kyma cannot be installed on Kubernetes

**Answer:**  
> **C) SAP BTP, Kyma Runtime is a managed service with SLAs and a hosted dashboard, while Open-Source Kyma requires self-management**

---

### 3. Which of the following is NOT a Kyma module?
- **A)** Istio
- **B)** API Gateway
- **C)** Serverless
- **D)** Prometheus

**Answer:**  
> **D) Prometheus**

---

### 4. What is the purpose of the Kyma Application Connector module?
- **A)** To provide persistent storage for Kubernetes
- **B)** To manage user authentication
- **C)** To simplify and secure the connection between external solutions and Kyma
- **D)** To provide a dashboard for monitoring

**Answer:**  
> **C) To simplify and secure the connection between external solutions and Kyma**

---

### 5. Which Kyma module is responsible for providing a service mesh and secure microservice communication?
- **A)** Serverless
- **B)** Telemetry
- **C)** Eventing
- **D)** Istio

**Answer:**  
> **D) Istio**

---

### 6. What is the main function of the Kyma Eventing module?
- **A)** To provide persistent storage for applications
- **B)** To enable asynchronous communication and event-driven workflows
- **C)** To manage user authentication
- **D)** To provide a dashboard for monitoring

**Answer:**  
> **B) To enable asynchronous communication and event-driven workflows**

---

### 7. Which Kyma module is responsible for collecting and analyzing metrics, logs, and traces?
- **A)** Telemetry
- **B)** Serverless
- **C)** API Gateway
- **D)** Keda

**Answer:**  
> **A) Telemetry**

---

### 8. What is the purpose of the Kyma API Gateway module?
- **A)** To provide a single point of entry for external communication and manage security
- **B)** To scale workloads based on events
- **C)** To connect external solutions to Kyma
- **D)** To provide persistent storage

**Answer:**  
> **A) To provide a single point of entry for external communication and manage security**

---

### 9. Which Kyma module enables event-driven autoscaling of Kubernetes workloads?
- **A)** Istio
- **B)** Keda
- **C)** NATS
- **D)** Application Connector

**Answer:**  
> **B) Keda**

---

### 10. What is the role of the NATS module in Kyma?
- **A)** To provide a service mesh for microservices
- **B)** To provide a dashboard for monitoring
- **C)** To manage distributed persistence and event delivery
- **D)** To manage user authentication

**Answer:**  
> **C) To manage distributed persistence and event delivery**

---

### 11. In the context of Kyma, what does "serverless" mean?
- **A)** The developer focuses on code and business logic, while the platform abstracts away server management
- **B)** There are no servers involved at all
- **C)** All applications run on physical servers only
- **D)** Applications must be stateless

**Answer:**  
> **A) The developer focuses on code and business logic, while the platform abstracts away server management**

---

### 12. Which of the following is NOT a benefit of SAP BTP, Kyma runtime?
- **A)** Integration with other SAP services and products
- **B)** Zero infrastructure management and maintenance effort
- **C)** Out-of-the-box Kyma modules
- **D)** Requirement to manually install and update Kubernetes

**Answer:**  
> **D) Requirement to manually install and update Kubernetes**

---

### 13. Which open-source project does SAP use to provision and manage the underlying Kubernetes clusters for Kyma runtime?
- **A)** Helm
- **B)** Gardener
- **C)** Prometheus
- **D)** Linkerd

**Answer:**  
> **B) Gardener**

---

### 14. What is the role of the "seed cluster" in SAP Gardener?
- **A)** It is the cluster where user applications run
- **B)** It stores all cluster data
- **C)** It provisions and manages the shoot clusters, performing updates and ensuring health
- **D)** It is used for backup and restore only

**Answer:**  
> **C) It provisions and manages the shoot clusters, performing updates and ensuring health**

---

### 15. Which of the following statements is TRUE about namespaces in Kyma runtime?
- **A)** All resources must be deployed in the default namespace
- **B)** The kyma-system namespace is used for Kyma modules, while istio-system and kube-system are used for other system-level resources
- **C)** Namespaces are not supported in Kyma runtime
- **D)** Only one namespace can exist in a Kyma cluster

**Answer:**  
> **B) The kyma-system namespace is used for Kyma modules, while istio-system and kube-system are used for other system-level resources**

---

### 16. What can you view in the Kyma dashboard for the kyma-system namespace?
- **A)** Only the list of Pods
- **B)** The status, health, and resource consumption of objects deployed by Kyma modules
- **C)** Only user-created resources
- **D)** Only network policies

**Answer:**  
> **B) The status, health, and resource consumption of objects deployed by Kyma modules**

---

### 17. Which user interfaces can you use to manage your Kyma cluster (There are three correct answers)?

- **A)** Kyma CLI
- **B)** Kyma dashboard
- **C)** kubectl
- **D)** pip

**Answer:**  
> **A) Kyma CLI**  
> **B) Kyma dashboard**  
> **C) kubectl**

---

### 18. Gardener is a Kubernetes like container orchestrator.
- **A)** True
- **B)** False

**Answer:**  
> **B) False**

---

### 19. How do Kubernetes workloads differ from lower-level objects like Pods?
- **A)** Workloads are higher-level abstractions that manage Pods for you
- **B)** Workloads are used only for networking
- **C)** Pods can manage workloads
- **D)** Workloads cannot be used to deploy applications

**Answer:**  
> **A) Workloads are higher-level abstractions that manage Pods for you**

---

### 20. What is a key advantage of using workloads instead of managing Pods directly?
- **A)** Workloads allow for automated scaling, self-healing, and easier updates
- **B)** Pods provide more automation than workloads
- **C)** Workloads cannot be used for stateless applications
- **D)** Pods are more reliable than workloads

**Answer:**  
> **A) Workloads allow for automated scaling, self-healing, and easier updates**

---

### 21. Which of the following statements is TRUE about the relationship between workloads and Pods?
- **A)** Pods and workloads are the same thing
- **B)** Pods create and manage workloads
- **C)** Workloads are only used for persistent storage
- **D)** Workloads create and manage Pods based on the desired state defined by the user

**Answer:**  
> **D) Workloads create and manage Pods based on the desired state defined by the user**

---

### 22. What is the main difference between a workload and a service in Kubernetes?
- **A)** Both are used only for persistent storage
- **B)** A workload provides network access, while a service manages application scaling
- **C)** A workload manages Pods and their lifecycle, while a service provides stable network access to Pods
- **D)** A service is used to create Pods, while a workload is used for networking

**Answer:**  
> **C) A workload manages Pods and their lifecycle, while a service provides stable network access to Pods**

---

### 23. What is a Serverless Function in Kyma?
- **A)** A type of persistent storage
- **B)** A workload type that allows you to run code without managing the container image or infrastructure
- **C)** A network policy
- **D)** A Kubernetes namespace

**Answer:**  
> **B) A workload type that allows you to run code without managing the container image or infrastructure**

---

### 24. Which of the following are valid ways to invoke a Serverless Function in Kyma? (Choose two)
- **A)** HTTP request
- **B)** Event
- **C)** K8s job start
- **D)** Manual pod restart

**Answer:**  
> **A) HTTP request**  
> **B) Event**

---

### 25. What is the main benefit of using a Deployment in Kubernetes?
- **A)** It provides persistent storage for applications
- **B)** It allows you to declaratively manage application updates, scaling, and rollbacks with zero downtime
- **C)** It is used only for networking
- **D)** It is required for creating namespaces

**Answer:**  
> **B) It allows you to declaratively manage application updates, scaling, and rollbacks with zero downtime**

---

### 26. Which Kubernetes object does a Deployment manage directly?
- **A)** Pods
- **B)** ReplicaSets
- **C)** Services
- **D)** Namespaces

**Answer:**  
> **B) ReplicaSets**

---

### 27. What is the default deployment strategy in Kubernetes?
- **A)** Blue/Green
- **B)** Recreate
- **C)** RollingUpdate
- **D)** Canary

**Answer:**  
> **C) RollingUpdate**

---

### 28. Which field in a Deployment manifest specifies the number of application instances to run?
- **A)** selector
- **B)** template
- **C)** replicas
- **D)** strategy

**Answer:**  
> **C) replicas**

---

### 29. Which of the following are common types of Kubernetes workloads? (Choose all that apply)
- **A)** Deployment
- **B)** StatefulSet
- **C)** DaemonSet
- **D)** Job

**Answer:**  
> **A) Deployment**  
> **B) StatefulSet**  
> **C) DaemonSet**  
> **D) Job**

---

### 30. What is the main difference between the Rolling Update and Recreate deployment strategies in Kubernetes?
- **A)** Rolling Update updates Pods one at a time with zero downtime, while Recreate deletes all old Pods before creating new ones
- **B)** Recreate is the default strategy, Rolling Update is not supported
- **C)** Rolling Update deletes all Pods at once, Recreate updates them one by one
- **D)** Both strategies always cause downtime

**Answer:**  
> **A) Rolling Update updates Pods one at a time with zero downtime, while Recreate deletes all old Pods before creating new ones**

---

### 31. What is the purpose of Deployment History in Kubernetes?
- **A)** To store application logs
- **B)** To allow you to check previous versions and roll back to a previous state if needed
- **C)** To manage network policies
- **D)** To monitor resource usage

**Answer:**  
> **B) To allow you to check previous versions and roll back to a previous state if needed**

---

### 32. How can you scale a Deployment in Kubernetes?
- **A)** By updating the replicas field in the Deployment manifest or using kubectl scale
- **B)** By creating more namespaces
- **C)** By increasing the number of Services
- **D)** By changing the container image

**Answer:**  
> **A) By updating the replicas field in the Deployment manifest or using kubectl scale**

---

### 33. What is Helm in the context of Kubernetes?
- **A)** A monitoring tool
- **B)** A package manager that simplifies the installation and management of Kubernetes applications
- **C)** A network policy controller
- **D)** A container runtime

**Answer:**  
> **B) A package manager that simplifies the installation and management of Kubernetes applications**

---

### 34. What is a Helm chart?
- **A)** A single YAML file for a Pod
- **B)** A monitoring dashboard
- **C)** A type of Kubernetes Service
- **D)** A package of pre-configured Kubernetes resources that can be deployed as a unit

**Answer:**  
> **D) A package of pre-configured Kubernetes resources that can be deployed as a unit**

---

### 35. Which file in a Helm chart contains the default configuration values for the chart?
- **A)** Chart.yaml
- **B)** README.md
- **C)** deployment.yaml
- **D)** values.yaml

**Answer:**  
> **D) values.yaml**

---

### 36. What is the purpose of templates in Helm charts?
- **A)** To provide static manifests only
- **B)** To store container images
- **C)** To allow parameterization and reuse of manifest files using variables
- **D)** To define network policies

**Answer:**  
> **C) To allow parameterization and reuse of manifest files using variables**

---

### 37. Which Helm CLI command is used to install a chart?
- **A)** helm upgrade
- **B)** helm install
- **C)** helm delete
- **D)** helm create

**Answer:**  
> **B) helm install**

---

### 38. What is the purpose of the Chart.yaml file in a Helm chart?
- **A)** It contains the main configuration values for the chart
- **B)** It provides metadata about the chart, such as name, version, and description
- **C)** It defines the container images to use
- **D)** It stores the deployment history

**Answer:**  
> **B) It provides metadata about the chart, such as name, version, and description**

---

### 39. What is typically stored in the charts/ directory of a Helm chart?
- **A)** The main chart metadata
- **B)** The rendered manifests
- **C)** The default values for the chart
- **D)** Subcharts or dependencies used by the main chart

**Answer:**  
> **D) Subcharts or dependencies used by the main chart**

---

### 40. What is the purpose of the templates/ directory in a Helm chart?
- **A)** To store static YAML files only
- **B)** To store template files that are rendered into Kubernetes manifests using values and variables
- **C)** To store container images
- **D)** To store Helm CLI commands

**Answer:**  
> **B) To store template files that are rendered into Kubernetes manifests using values and variables**

---

### 41. What is the crds/ directory used for in a Helm chart?
- **A)** To store custom resource definitions (CRDs) that should be installed with the chart
- **B)** To store container images
- **C)** To store Helm CLI plugins
- **D)** To store deployment logs

**Answer:**  
> **A) To store custom resource definitions (CRDs) that should be installed with the chart**

---

### 42. What is the purpose of the Helm dry-run feature?
- **A)** To permanently install a chart in the cluster
- **B)** To preview the rendered Kubernetes manifests without applying them to the cluster
- **C)** To delete a Helm release
- **D)** To update the Helm CLI

**Answer:**  
> **B) To preview the rendered Kubernetes manifests without applying them to the cluster**

---

### 43. What is the main purpose of a DaemonSet in Kubernetes?
- **A)** To ensure a Pod runs on every (or a subset of) node(s) in the cluster
- **B)** To manage application updates with zero downtime
- **C)** To provide network access to Pods
- **D)** To create namespaces

**Answer:**  
> **A) To ensure a Pod runs on every (or a subset of) node(s) in the cluster**

---

### 44. Which of the following is a typical use case for a DaemonSet?
- **A)** Running a logging or monitoring agent on every node
- **B)** Managing database migrations
- **C)** Exposing a web service
- **D)** Creating user accounts

**Answer:**  
> **A) Running a logging or monitoring agent on every node**

---

### 45. How does a DaemonSet differ from a ReplicaSet?
- **A)** A DaemonSet ensures one Pod per node, while a ReplicaSet ensures a specified number of Pods anywhere in the cluster
- **B)** A DaemonSet manages Services, while a ReplicaSet manages Deployments
- **C)** A ReplicaSet is used for persistent storage, while a DaemonSet is not
- **D)** There is no difference

**Answer:**  
> **A) A DaemonSet ensures one Pod per node, while a ReplicaSet ensures a specified number of Pods anywhere in the cluster**

---

### 46. Which controller is responsible for scheduling Pods for a DaemonSet?
- **A)** kube-scheduler
- **B)** DaemonSet controller
- **C)** Deployment controller
- **D)** Service controller

**Answer:**  
> **B) DaemonSet controller**

---

### 47. How can you restrict a DaemonSet to run Pods only on specific nodes?
- **A)** By using a node selector in the DaemonSet manifest
- **B)** By setting the number of replicas
- **C)** By creating a Service
- **D)** By using a PersistentVolumeClaim

**Answer:**  
> **A) By using a node selector in the DaemonSet manifest**

---

### 48. What is the main purpose of a Job in Kubernetes?
- **A)** To run a workload only once to completion
- **B)** To provide persistent storage
- **C)** To expose a web service
- **D)** To manage network policies

**Answer:**  
> **A) To run a workload only once to completion**

---

### 49. Which field in a Job manifest specifies how many times a failed Job should be retried before being marked as failed?
- **A)** completions
- **B)** schedule
- **C)** parallelism
- **D)** backoffLimit

**Answer:**  
> **D) backoffLimit**

---

### 50. What is a parallel Job in Kubernetes?
- **A)** A Job that runs multiple Pods in parallel to complete a set number of tasks
- **B)** A Job that runs only on a single node
- **C)** A Job that never terminates
- **D)** A Job that manages Services

**Answer:**  
> **A) A Job that runs multiple Pods in parallel to complete a set number of tasks**

---

### 51. What is the purpose of a CronJob in Kubernetes?
- **A)** To run a workload only once
- **B)** To schedule Jobs to run periodically at fixed times or intervals
- **C)** To manage network policies
- **D)** To expose a web service

**Answer:**  
> **B) To schedule Jobs to run periodically at fixed times or intervals**

---

### 52. How does a Job differ from a Deployment in Kubernetes?
- **A)** A Job runs Pods to completion and then terminates, while a Deployment manages long-running Pods
- **B)** A Job manages Services, while a Deployment manages DaemonSets
- **C)** A Deployment is used for batch jobs, while a Job is used for web services
- **D)** There is no difference

**Answer:**  
> **A) A Job runs Pods to completion and then terminates, while a Deployment manages long-running Pods**

---

### 53. What is the difference between horizontal and vertical scaling in Kubernetes?
- **A)** Horizontal scaling changes the number of Pods, vertical scaling changes the resources (CPU/memory) of a Pod
- **B)** Horizontal scaling changes the resources of a Pod, vertical scaling changes the number of Pods
- **C)** Both terms mean the same thing
- **D)** Only vertical scaling is supported in Kubernetes

**Answer:**  
> **A) Horizontal scaling changes the number of Pods, vertical scaling changes the resources (CPU/memory) of a Pod**

---

### 54. What is the main purpose of a Horizontal Pod Autoscaler (HPA) in Kubernetes?
- **A)** To scale the resources (CPU/memory) of a single Pod vertically
- **B)** To automatically scale the number of Pods in a Deployment or ReplicaSet based on observed metrics
- **C)** To create namespaces
- **D)** To manage network policies

**Answer:**  
> **B) To automatically scale the number of Pods in a Deployment or ReplicaSet based on observed metrics**

---

### 55. Which of the following metrics can be used by an HPA to scale Pods?
- **A)** CPU usage
- **B)** Memory usage
- **C)** Custom metrics
- **D)** All of the above

**Answer:**  
> **D) All of the above**

---

### 56. What do the minReplicas and maxReplicas fields define in an HPA manifest?
- **A)** The minimum and maximum CPU usage allowed for a Pod
- **B)** The minimum and maximum number of Pods that can be created by the HPA
- **C)** The minimum and maximum memory for a container
- **D)** The minimum and maximum number of namespaces

**Answer:**  
> **B) The minimum and maximum number of Pods that can be created by the HPA**

---

### 57. Which workload type is suitable for a stateful workload, such as a database?
- **A)** Pod
- **B)** ReplicaSet
- **C)** Deployment
- **D)** StatefulSet
- **E)** DaemonSet

**Answer:**  
> **D) StatefulSet**

---

### 58. Which components can you differentiate in a Helm chart?
Choose the correct answer.
- **A)** "Chart.yaml", "values.yaml", "charts/", "templates/"
- **B)** "helm.yaml", "parameters.yaml", "charts/", "manifests/"
- **C)** "Kubenetes.yaml", "parameters.yaml", "charts/", "manifests/"

**Answer:**  
> **A) "Chart.yaml", "values.yaml", "charts/", "templates/"**

---

