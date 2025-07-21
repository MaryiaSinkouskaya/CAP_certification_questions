## Module 5 questions. Developing Applications in SAP BTP, Kyma Runtime
## Using Kyma Eventing
## Using Kubernetes Storage and StatefulSets

---

### 1. What is the main purpose of the Kyma Eventing module?
- **A)** To simplify the process of subscribing to and publishing events
- **B)** To manage persistent storage for applications
- **C)** To provide a user interface for Kubernetes
- **D)** To deploy new Pods automatically

**Answer:**  
> **A) To simplify the process of subscribing to and publishing events**

---

### 2. Which messaging technology is used as the default backend for Kyma Eventing?
- **A)** RabbitMQ
- **B)** NATS
- **C)** Kafka
- **D)** Redis

**Answer:**  
> **B) NATS**

---

### 3. What messaging pattern is Kyma Eventing based on?
- **A)** Request/Response
- **B)** Batch Processing
- **C)** Point-to-Point
- **D)** Publish/Subscribe

**Answer:**  
> **D) Publish/Subscribe**

---

### 4. Which of the following technologies are involved in the Kyma Eventing process? (Choose all that apply)
- **A)** NATS JetStream
- **B)** HTTP POST requests
- **C)** PersistentVolumeClaims
- **D)** Subscription Custom Resources

**Answer:**  
> **A) NATS JetStream**  
> **B) HTTP POST requests**  
> **D) Subscription Custom Resources**

---

### 5. Which of the following is a valid use case for Kyma Eventing in SAP BTP, Kyma runtime?
- **A)** Consuming business events from connected SAP and non-SAP solutions
- **B)** Managing user authentication
- **C)** Creating persistent storage volumes
- **D)** Monitoring cluster health

**Answer:**  
> **A) Consuming business events from connected SAP and non-SAP solutions**

---

### 6. What is the benefit of using the Kyma dashboard for Eventing?
- **A)** It allows you to view and update Subscriptions for workloads or at the namespace level
- **B)** It provides persistent storage for events
- **C)** It automatically scales Pods
- **D)** It manages network policies

**Answer:**  
> **A) It allows you to view and update Subscriptions for workloads or at the namespace level**

---

### 7. Which of the following technologies are used throughout the Kyma Eventing process? (There are two correct answers.)
- **A)** Apache Kafka
- **B)** MQTT
- **C)** JetStream
- **D)** NATS

**Answer:**  
> **C) JetStream**  
> **D) NATS**

---

### 8. What is the main reason for using persistent storage in Kubernetes?
- **A)** To store temporary files that are deleted when a Pod restarts
- **B)** To increase the number of running Pods
- **C)** To ensure data is retained even if a Pod is deleted or crashes
- **D)** To manage user authentication

**Answer:**  
> **C) To ensure data is retained even if a Pod is deleted or crashes**

---

### 9. Which Kubernetes resource represents a piece of physical storage in the cluster?
- **A)** PersistentVolumeClaim
- **B)** ConfigMap
- **C)** StorageClass
- **D)** PersistentVolume

**Answer:**  
> **D) PersistentVolume**

---

### 10. What is the purpose of a PersistentVolumeClaim (PVC) in Kubernetes?
- **A)** To define a storage class
- **B)** To request storage from a PersistentVolume for a Pod
- **C)** To store application logs
- **D)** To manage network policies

**Answer:**  
> **B) To request storage from a PersistentVolume for a Pod**

---

### 11. What is a StorageClass in Kubernetes?
- **A)** A way to describe different types of storage offered by the cluster administrator
- **B)** A type of Pod
- **C)** A user account
- **D)** A network policy

**Answer:**  
> **A) A way to describe different types of storage offered by the cluster administrator**

---

### 12. In SAP BTP, Kyma runtime, who provides the underlying physical storage for PersistentVolumes?
- **A)** The application developer
- **B)** The end user
- **C)** The hyperscaler (e.g., AWS, Azure, GCP) via Gardener
- **D)** The Kubernetes API server

**Answer:**  
> **C) The hyperscaler (e.g., AWS, Azure, GCP) via Gardener**

---

### 13. What happens to data stored in a container's local file system if the container crashes or is deleted?
- **A)** The data is retained and available to new containers
- **B)** The data is lost
- **C)** The data is automatically backed up
- **D)** The data is moved to a PersistentVolume

**Answer:**  
> **B) The data is lost**

---

### 14. How does a Pod access persistent storage in Kubernetes?
- **A)** By mounting a PersistentVolumeClaim as a volume at a specific path
- **B)** By creating a new PersistentVolume
- **C)** By using a ConfigMap
- **D)** By scaling the number of Pods

**Answer:**  
> **A) By mounting a PersistentVolumeClaim as a volume at a specific path**

---

### 15. Where can you view PersistentVolumeClaims in the Kyma dashboard?
- **A)** At the namespace level
- **B)** At the cluster level only
- **C)** In the kube-system namespace
- **D)** In the application logs

**Answer:**  
> **A) At the namespace level**

---

### 16. Which of the following best describes the difference between a PersistentVolume (PV) and a PersistentVolumeClaim (PVC) in Kubernetes?
- **A)** A PV is a request for storage, while a PVC is the actual storage resource
- **B)** Both PV and PVC are types of Pods
- **C)** Both PV and PVC are used to store application logs
- **D)** A PV is the actual storage resource, while a PVC is a request for storage

**Answer:**  
> **D) A PV is the actual storage resource, while a PVC is a request for storage**

---

### 17. True or False: StatefulSets in Kubernetes are designed for managing stateful applications that require stable network identities and persistent storage.
- **A)** True
- **B)** False

**Answer:**  
> **A) True**

---

### 18. Which of the following is NOT a feature provided by StatefulSets?
- **A)** Stable, unique network identifiers for Pods
- **B)** Ordered, graceful deployment and scaling
- **C)** Random Pod names and unordered scaling
- **D)** Stable, persistent storage for each Pod

**Answer:**  
> **C) Random Pod names and unordered scaling**

---

### 19. How are Pods named when created by a StatefulSet?
- **A)** They are named sequentially with an index (e.g., my-app-0, my-app-1)
- **B)** They are given random hashes at the end of their names
- **C)** They are named after the node they run on
- **D)** They use the name of the Deployment

**Answer:**  
> **A) They are named sequentially with an index (e.g., my-app-0, my-app-1)**

---

### 20. What is the purpose of a headless service in the context of StatefulSets?
- **A)** To provide a single cluster IP for all Pods
- **B)** To store application configs
- **C)** To manage cluster access policies
- **D)** To allow direct access to each Pod by its stable DNS name

**Answer:**  
> **D) To allow direct access to each Pod by its stable DNS name**

---

### 22. True or False: A headless service in Kubernetes is created by setting the clusterIP field to None, allowing direct access to each Pod by its DNS name.
- **A)** True
- **B)** False

**Answer:**  
> **A) True**

---

### 23. What is the purpose of connecting a PersistentVolume to a StatefulSet in Kubernetes?
- **A)** To provide temporary storage for stateless applications
- **B)** To ensure that data stored by a stateful application persists even if the Pod is deleted or recreated
- **C)** To manage network policies
- **D)** To scale the number of Pods automatically

**Answer:**  
> **B) To ensure that data stored by a stateful application persists even if the Pod is deleted or recreated**

---

### 24. Which of the following steps is required to connect storage to a StatefulSet for a database like Postgres?
- **A)** Create a PersistentVolume, a PersistentVolumeClaim, and reference the claim in the StatefulSet
- **B)** Only create a ConfigMap
- **C)** Only create a Deployment
- **D)** Only create a Service

**Answer:**  
> **A) Create a PersistentVolume, a PersistentVolumeClaim, and reference the claim in the StatefulSet**

---

### 25. In the context of StatefulSets, what happens if you delete a Pod and it is recreated?
- **A)** The Pod gets a new name and loses its data
- **B)** The Pod is not recreated
- **C)** The Pod keeps the same name and can access its previous data via the PersistentVolume
- **D)** The PersistentVolume is deleted

**Answer:**  
> **C) The Pod keeps the same name and can access its previous data via the PersistentVolume**

---

### 26. Which command would you use to check if a PersistentVolumeClaim is bound to a PersistentVolume?
- **A)** kubectl get pv
- **B)** kubectl get service
- **C)** kubectl get statefulset
- **D)** kubectl get pvc <claim-name>

**Answer:**  
> **D) kubectl get pvc <claim-name>**

---
