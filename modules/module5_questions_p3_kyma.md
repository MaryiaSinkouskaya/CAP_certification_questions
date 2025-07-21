## Module 5 questions. Developing Applications in SAP BTP, Kyma Runtime

## Using Services to Create Internal and External Communication with Kubernetes
## Using Service Meshes with Istio
---

### 1. In Kubernetes, what is the primary function of a Service?
- **A)** To provide long-term storage for application data
- **B)** To execute container images on nodes
- **C)** To organize resources into namespaces
- **D)** To group Pods and define how they are accessed over the network

**Answer:**  
> **D) To group Pods and define how they are accessed over the network**

---

### 2. Which of the following best describes the main purpose of a Kubernetes Service?
- **A)** To manage the lifecycle of Pods
- **B)** To store application logs
- **C)** To provide stable networking endpoints and load-balance traffic to a dynamic set of Pods
- **D)** To schedule containers on nodes

**Answer:**  
> **C) To provide stable networking endpoints and load-balance traffic to a dynamic set of Pods**

---

### 3. How does a Service differ from a Deployment in Kubernetes?
- **A)** A Service manages Pods directly, while a Deployment provides stable networking
- **B)** A Deployment manages the lifecycle and scaling of Pods, while a Service provides network access to Pods
- **C)** Both are used for persistent storage
- **D)** There is no difference

**Answer:**  
> **B) A Deployment manages the lifecycle and scaling of Pods, while a Service provides network access to Pods**

---

### 4. Which of the following is TRUE about the relationship between Services and Pods?
- **A)** Services provide stable networking endpoints and can load-balance traffic to a dynamic set of Pods
- **B)** Services are deleted when Pods are deleted
- **C)** Pods manage the lifecycle of Services
- **D)** Services can only target a single Pod at a time

**Answer:**  
> **A) Services provide stable networking endpoints and can load-balance traffic to a dynamic set of Pods**

---

### 5. What mechanism do Services use to select which Pods to target?
- **A)** Node selectors
- **B)** Label selectors
- **C)** Annotations
- **D)** Resource quotas

**Answer:**  
> **B) Label selectors**

---

### 6. Which type of Service would you use to expose an application to external traffic from outside the cluster?
- **A)** ClusterIP
- **B)** NodePort
- **C)** LoadBalancer
- **D)** Headless

**Answer:**  
> **C) LoadBalancer**

---

### 7. Which of the following is NOT a valid Kubernetes Service type?
- **A)** ClusterIP
- **B)** NodePort
- **C)** LoadBalancer
- **D)** ReplicaSet

**Answer:**  
> **D) ReplicaSet**

---

### 8. What is the default Service type in Kubernetes?
- **A)** NodePort
- **B)** LoadBalancer
- **C)** ClusterIP
- **D)** Headless

**Answer:**  
> **C) ClusterIP**

---

### 9. Which object would you use to provide HTTP routing and TLS termination for multiple Services in a Kubernetes cluster?
- **A)** Pod
- **B)** Deployment
- **C)** Ingress
- **D)** ConfigMap

**Answer:**  
> **C) Ingress**

---

### 10. Which of the following statements is TRUE about Headless Services in Kubernetes?
- **A)** They provide a stable IP address for accessing Pods
- **B)** They do not allocate a cluster IP and are used for direct Pod-to-Pod communication
- **C)** They are only used for external traffic
- **D)** They are required for all Deployments

**Answer:**  
> **B) They do not allocate a cluster IP and are used for direct Pod-to-Pod communication**

---

### 11. Which command lists all Services in the current Kubernetes namespace?
- **A)** kubectl get pods
- **B)** kubectl get deployments
- **C)** kubectl get svc
- **D)** kubectl describe service

**Answer:**  
> **C) kubectl get svc**

---

### 13. What is the main purpose of the API Gateway module in Kyma?
- **A)** To provide persistent storage for applications
- **B)** To expose Services and Functions outside the Kyma cluster
- **C)** To manage namespaces
- **D)** To schedule Pods on nodes

**Answer:**  
> **B) To expose Services and Functions outside the Kyma cluster**

---

### 14. Which open-source project is the Kyma API Gateway based on?
- **A)** Prometheus
- **B)** Istio
- **C)** Helm
- **D)** NATS

**Answer:**  
> **B) Istio**

---

### 15. What is the role of the kyma-gateway in the Kyma API Gateway module?
- **A)** It stores application logs for all services
- **B)** It manages internal DNS resolution for services
- **C)** It is the main entry point for all external traffic into the Kyma cluster
- **D)** It provides persistent storage for Pods

**Answer:**  
> **C) It is the main entry point for all external traffic into the Kyma cluster**

---

### 16. Which component is used for authorizing incoming HTTP requests in the Kyma API Gateway?
- **A)** Ory Oathkeeper
- **B)** Prometheus
- **C)** Grafana
- **D)** Keda

**Answer:**  
> **A) Ory Oathkeeper**

---

### 17. What is the purpose of an APIRule Custom Resource (CR) in Kyma?
- **A)** To define a new namespace
- **B)** To expose a Kubernetes Service via the API Gateway
- **C)** To create a PersistentVolume
- **D)** To deploy a new Pod

**Answer:**  
> **B) To expose a Kubernetes Service via the API Gateway**

---


### 18. Which access strategies can be defined in an APIRule for securing endpoints? (Choose 3 apply)
- **A)** noAuth
- **B)** jwt
- **C)** extAuth
- **D)** basicAuth

**Answer:**  
> **A) noAuth**  
> **B) jwt**  
> **C) extAuth**

---

### 19. How can you create an APIRule in Kyma? (Choose two)
- **A)** Using a YAML manifest
- **B)** Using the Kyma dashboard form-based view
- **C)** By editing the kubelet configuration
- **D)** By running a Pod directly

**Answer:**  
> **A) Using a YAML manifest**  
> **B) Using the Kyma dashboard form-based view**

---

### 25. What is the primary function of the Istio Ingress Gateway in Kyma?
- **A)** To store application logs
- **B)** To route external traffic into the cluster and forward it to the correct Service
- **C)** To manage persistent storage for Pods
- **D)** To schedule Pods on nodes

**Answer:**  
> **B) To route external traffic into the cluster and forward it to the correct Service**

---

### 26. Which component acts as the application-based service proxy in the Kyma API Gateway?
- **A)** Ory Oathkeeper
- **B)** Envoy Proxy
- **C)** Prometheus
- **D)** Grafana

**Answer:**  
> **B) Envoy Proxy**

---

### 27. What is the main responsibility of Ory Oathkeeper in the Kyma API Gateway architecture?
- **A)** To provide monitoring and logging
- **B)** To authorize incoming HTTP requests based on access rules
- **C)** To manage DNS resolution
- **D)** To deploy new Pods

**Answer:**  
> **B) To authorize incoming HTTP requests based on access rules**

---

### 28. How do Istio Ingress Gateway and Ory Oathkeeper work together in the Kyma API Gateway?
- **A)** Ory Oathkeeper routes traffic, and Istio Ingress Gateway authorizes requests
- **B)** Istio Ingress Gateway handles incoming traffic, and Ory Oathkeeper enforces access rules on the traffic
- **C)** Both components are responsible for persistent storage
- **D)** They are unrelated and operate independently

**Answer:**  
> **B) Istio Ingress Gateway handles incoming traffic, and Ory Oathkeeper enforces access rules on the traffic**

---

### 29. What is a service mesh in the context of Kubernetes?
- **A)** A type of persistent storage
- **B)** An infrastructure layer that manages communication between microservices
- **C)** A tool for building container images
- **D)** A monitoring dashboard

**Answer:**  
> **B) An infrastructure layer that manages communication between microservices**

---

### 30. Which of the following is NOT a core benefit of using a service mesh?
- **A)** Security features like mutual TLS (mTLS)
- **B)** Observability with tracing and metrics
- **C)** Traffic management and resilience
- **D)** Automatic scaling of nodes

**Answer:**  
> **D) Automatic scaling of nodes**

---

### 31. What security feature does a service mesh provide for microservice communication?
- **A)** Manual encryption configuration in each service
- **B)** Out-of-the-box mutual TLS (mTLS) for service-to-service communication
- **C)** Only basic authentication
- **D)** No security features

**Answer:**  
> **B) Out-of-the-box mutual TLS (mTLS) for service-to-service communication**

---

### 32. In a Kubernetes service mesh, what is the function of the sidecar proxy that is injected alongside each service?
- **A)** It stores backup copies of service data
- **B)** It intercepts and manages all inbound and outbound network traffic for the service
- **C)** It schedules Pods on nodes
- **D)** It provides a user interface for the service

**Answer:**  
> **B) It intercepts and manages all inbound and outbound network traffic for the service**

---

### 33. What role does the control plane play in a service mesh architecture?
- **A)** It runs the main application code for each service
- **B)** It orchestrates and updates the configuration of all proxies in the mesh
- **C)** It stores persistent volumes for the cluster
- **D)** It handles direct communication between Pods

**Answer:**  
> **B) It orchestrates and updates the configuration of all proxies in the mesh**

---

### 34. In a service mesh, what is the main responsibility of the data plane?
- **A)** Managing configuration and policy for the mesh
- **B)** Handling the actual flow of network traffic between services through proxies
- **C)** Storing logs and metrics for observability
- **D)** Deploying new microservices automatically

**Answer:**  
> **B) Handling the actual flow of network traffic between services through proxies**

---

### 35. Which service mesh solution is commonly used in Kubernetes and Kyma?
- **A)** Prometheus
- **B)** Istio
- **C)** Helm
- **D)** NATS

**Answer:**  
> **B) Istio**

---

### 36. What is a key advantage of using a service mesh for microservices written in different languages?
- **A)** It requires all services to use the same programming language
- **B)** It centralizes networking and security features, decoupling them from application logic
- **C)** It only supports HTTP traffic
- **D)** It eliminates the need for service discovery

**Answer:**  
> **B) It centralizes networking and security features, decoupling them from application logic**

---

### 38. Which proxy technology does Istio use to manage and route service traffic?
- **A)** NGINX
- **B)** Envoy
- **C)** Apache
- **D)** Traefik

**Answer:**  
> **B) Envoy**

---

### 40. Where are Istio's main components installed in a Kyma cluster?
- **A)** default namespace
- **B)** istio-system namespace
- **C)** kyma-system namespace
- **D)** kube-system namespace

**Answer:**  
> **B) istio-system namespace**

---

### 41. What happens when you expose a workload in Kyma using an APIRule?
- **A)** Only a Kubernetes Service is created
- **B)** Istio resources such as VirtualService and AuthorizationPolicy are automatically created in the background
- **C)** The workload is exposed without any security module
- **D)** The workload is deleted

**Answer:**  
> **B) Istio resources such as VirtualService and AuthorizationPolicy are automatically created in the background**

---

### 42. Which Istio resource is used to define routing rules for HTTP requests based on path, headers, or query parameters?
- **A)** Gateway
- **B)** VirtualService
- **C)** DestinationRule
- **D)** ServiceAccount

**Answer:**  
> **B) VirtualService**

---

### 43. What is the purpose of an Istio DestinationRule?
- **A)** To define access policies for users
- **B)** To group service instances into subsets and apply policies to them
- **C)** To expose services to the internet
- **D)** To collect metrics from services

**Answer:**  
> **B) To group service instances into subsets and apply policies to them**

---

### 44. Which Istio resource acts as a load balancer at the edge of the mesh, handling incoming or outgoing HTTP/TCP connections?
- **A)** Gateway
- **B)** VirtualService
- **C)** ConfigMap
- **D)** Secret

**Answer:**  
> **A) Gateway**

---

### 45. What security protocol does Istio use to encrypt service-to-service communication?
- **A)** SSH
- **B)** Basic Auth
- **C)** Mutual TLS (mTLS)
- **D)** OAuth2

**Answer:**  
> **C) Mutual TLS (mTLS)**

---

### 46. Which of the following is NOT an observability feature provided by Istio?
- **A)** Distributed tracing
- **B)** Metrics collection
- **C)** Access logs
- **D)** Automatic scaling of Pods

**Answer:**  
> **D) Automatic scaling of Pods**

---

### 47. In Kyma, which module enriches and ships Istio's telemetry data to a backend for analysis?
- **A)** API Gateway
- **B)** Telemetry module
- **C)** Serverless module
- **D)** Eventing module

**Answer:**  
> **B) Telemetry module**

---

### 48. Which of the following statements is true? (There are two correct answers.)
- **A)** Istio is an open-source service mesh solution that extends Kubernetes.
- **B)** The Istio control plane intercepts and controls network communication.
- **C)** Istio has a control plane and a data plane.
- **D)** The Istio data plane manages the service mesh.

**Answer:**  
> **A) Istio is an open-source service mesh solution that extends Kubernetes.**  
> **C) Istio has a control plane and a data plane.**

---



