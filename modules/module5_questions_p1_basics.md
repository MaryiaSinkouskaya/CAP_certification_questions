## Module 5 questions. Developing Applications in SAP BTP, Kyma Runtime
## K8s basics

---

### 1. What is Kubernetes?
- **A)** A programming language
- **B)** An open-source platform for automating deployment, scaling, and management of containerized applications
- **C)** A type of database
- **D)** A web browser

**Answer:**  
> **B) An open-source platform for automating deployment, scaling, and management of containerized applications**

---

### 2. What is a Pod in Kubernetes?
- **A)** The smallest deployable unit that can run one or more containers
- **B)** A configuration file for deployments
- **C)** A cluster instance
- **D)** A type of persistent storage

**Answer:**  
> **A) The smallest deployable unit that can run one or more containers**

---

### 3. What is a Kubernetes cluster?
- **A)** A configuration file
- **B)** A single container
- **C)** A group of nodes that run containerized applications managed by Kubernetes
- **D)** A type of network policy

**Answer:**  
> **C) A group of nodes that run containerized applications managed by Kubernetes**

---

### 4. What is a node in Kubernetes?
- **A)** A database
- **B)** A type of service
- **C)** A machine (virtual or physical) that runs containerized applications as part of a cluster
- **D)** A configuration file

**Answer:**  
> **C) A machine (virtual or physical) that runs containerized applications as part of a cluster**

---

### 5. What is a container?
- **A)** A type of Kubernetes resource for networking
- **B)** A user account
- **C)** A lightweight, standalone, executable package that includes everything needed to run a piece of software
- **D)** A storage device

**Answer:**  
> **C) A lightweight, standalone, executable package that includes everything needed to run a piece of software**

---

### 6. You are deploying a multi-container application in Kubernetes. Which statement best describes how containers are grouped and managed within a Pod?
- **A)** Containers in a Pod share the same network namespace and can communicate via localhost
- **B)** Each container in a Pod has its own IP address and cannot share storage
- **C)** Containers in a Pod must run on different nodes
- **D)** Pods can only contain a single container by design

**Answer:**  
> **A) Containers in a Pod share the same network namespace and can communicate via localhost**

---

### 7. What is the purpose of the `kubectl` command-line tool?
- **A)** To monitor network traffic
- **B)** To create Docker images
- **C)** To write application code
- **D)** To interact with and manage Kubernetes clusters

**Answer:**  
> **D) To interact with and manage Kubernetes clusters**

---

### 8. What is a Kubernetes manifest?
- **A)** A log file for cluster events
- **B)** A YAML or JSON file that describes a desired state for a resource in the cluster
- **C)** A container image
- **D)** A user account

**Answer:**  
> **B) A YAML or JSON file that describes a desired state for a resource in the cluster**

---

### 9. You are tasked with deploying a new application using a manifest file. Which of the following best describes the role of the manifest in this process?
- **A)** It defines the desired state and configuration for Kubernetes resources in YAML or JSON format
- **B)** It stores runtime logs for the application
- **C)** It is used to build container images
- **D)** It manages user authentication for the cluster

**Answer:**  
> **A) It defines the desired state and configuration for Kubernetes resources in YAML or JSON format**

---

### 10. What is a label in Kubernetes?
- **A)** A type of container
- **B)** A network policy
- **C)** A key-value pair attached to objects for identification and selection
- **D)** A storage class

**Answer:**  
> **C) A key-value pair attached to objects for identification and selection**

---

### 11. What is a PersistentVolume in Kubernetes?
- **A)** A type of pod
- **B)** A network policy
- **C)** A container image
- **D)** A piece of storage in the cluster that has been provisioned by an administrator or dynamically provisioned

**Answer:**  
> **D) A piece of storage in the cluster that has been provisioned by an administrator or dynamically provisioned**

---

### 12. What is the purpose of a kubeconfig file?
- **A)** To define pod resource limits
- **B)** To store container logs
- **C)** To manage network policies
- **D)** To store configuration information for accessing Kubernetes clusters

**Answer:**  
> **D) To store configuration information for accessing Kubernetes clusters**


---


### 13. Your application requires persistent storage that must survive Pod restarts and rescheduling. Which Kubernetes resource should you use to provide this capability?
- **A)** ConfigMap
- **B)** Secret
- **C)** PersistentVolume and PersistentVolumeClaim
- **D)** NodePort

**Answer:**  
> **C) PersistentVolume and PersistentVolumeClaim**

---

### 14. What language was Kubernetes written in?
- **A)** Go
- **B)** Java
- **C)** C++
- **D)** C

**Answer:**  
> **A) Go**

---

### 15. An abstraction in Kubernetes which defines a logical set of pods and a policy to access them.
- **A)** node
- **B)** service
- **C)** cluster
- **D)** set

**Answer:**  
> **B) service**

---

### 16. Which of the following statements is TRUE regarding the relationship between Pods and Containers in Kubernetes?
- **A)** Each Pod can only contain a single container.
- **B)** A container can run multiple Pods.
- **C)** A Pod can contain one or more containers that share storage and network resources.
- **D)** Containers and Pods are the same thing in Kubernetes.

**Answer:**  
> **C) A Pod can contain one or more containers that share storage and network resources**

---

### 17. Which resource is responsible for ensuring that a specified number of identical Pods are always running in a Kubernetes cluster, even if some fail?
- **A)** Deployment
- **B)** ReplicaSet
- **C)** Service
- **D)** Node

**Answer:**  
> **B) ReplicaSet**

---

### 18. What is the main difference between a Deployment and a ReplicaSet in Kubernetes?
- **A)** Deployments manage ReplicaSets and provide declarative updates for Pods, while ReplicaSets only ensure a specified number of Pods are running.
- **B)** ReplicaSets manage Deployments and provide rolling updates.
- **C)** Deployments are used for networking, ReplicaSets for storage.
- **D)** There is no difference; they are synonyms.

**Answer:**  
> **A) Deployments manage ReplicaSets and provide declarative updates for Pods, while ReplicaSets only ensure a specified number of Pods are running.**

---

### 19. Which of the following best describes a Node in Kubernetes?
- **A)** A logical grouping of Pods
- **B)** A physical or virtual machine that runs containerized workloads as part of a cluster
- **C)** A YAML file describing resources
- **D)** A network endpoint for accessing services

**Answer:**  
> **B) A physical or virtual machine that runs containerized workloads as part of a cluster**

---

### 20. Which resource would you use to expose a set of Pods to external traffic and provide load balancing?
- **A)** ReplicaSet
- **B)** Deployment
- **C)** Service
- **D)** Node

**Answer:**  
> **C) Service**

---

### 21. In Kubernetes, which of the following is NOT a valid reason for a Pod to be recreated by the system?
- **A)** The Pod’s container process crashed
- **B)** The Node hosting the Pod failed
- **C)** The Pod was deleted manually
- **D)** The Service associated with the Pod was deleted

**Answer:**  
> **D) The Service associated with the Pod was deleted**

---

### 22. Which of the following best describes the difference between a Cluster and a Node in Kubernetes?
- **A)** A Cluster is a single machine, while a Node is a group of machines.
- **B)** A Node is a single machine (physical or virtual) in the Cluster; a Cluster is the collection of all Nodes managed by Kubernetes.
- **C)** A Cluster is a type of Pod, and a Node is a type of Service.
- **D)** There is no difference.

**Answer:**  
> **B) A Node is a single machine (physical or virtual) in the Cluster; a Cluster is the collection of all Nodes managed by Kubernetes.**

---

### 23. Which resource is responsible for rolling updates and rollbacks of application versions in Kubernetes?
- **A)** Pod
- **B)** ReplicaSet
- **C)** Deployment
- **D)** Service

**Answer:**  
> **C) Deployment**

---

### 24. Which of the following is TRUE about the relationship between Services and Pods?
- **A)** Services are ephemeral and are deleted when Pods are deleted.
- **B)** Services provide stable networking endpoints and can load-balance traffic to a dynamic set of Pods.
- **C)** Pods manage the lifecycle of Services.
- **D)** Services can only target a single Pod at a time.

**Answer:**  
> **B) Services provide stable networking endpoints and can load-balance traffic to a dynamic set of Pods.**

---

### 25. In Kubernetes, a ReplicaSet is responsible for providing declarative updates to Pods, including rolling updates and rollbacks.
- **A)** True
- **B)** False

**Answer:**  
> **B) False**

---

### 26. The kubeconfig file is required for authenticating and accessing a Kubernetes cluster using `kubectl`.
- **A)** True
- **B)** False

**Answer:**  
> **A) True**

---

### 27. Kubernetes ConfigMaps are used to store sensitive information such as passwords and API keys.
- **A)** True
- **B)** False

**Answer:**  
> **B) False**

---


