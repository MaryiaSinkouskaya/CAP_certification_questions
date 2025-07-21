## Module 5 questions. Developing Applications in SAP BTP, Kyma Runtime
## Using SAP BTP Service Management
## Performing Observability and Monitoring
## Using ConfigMaps and Secrets

---

### 1. What does SAP BTP Service Management enable you to do in a Kyma environment?
- **A)** Deploy and manage Kubernetes deployments and services
- **B)** Scale, deploy and delete Pods automatically
- **C)** Monitor application logs 
- **D)** Integrate and administer SAP BTP services within your cluster using the SAP BTP Operator

**Answer:**  
> **D) Integrate and administer SAP BTP services within your cluster using the SAP BTP Operator**

---

### 2. What is the SAP BTP Operator module based on?
- **A)** Kubernetes Operator pattern
- **B)** Helm charts
- **C)** StatefulSets
- **D)** ReplicaSets

**Answer:**  
> **A) Kubernetes Operator pattern**

---

### 3. Which API does the SAP BTP Operator module use to communicate between the Service Broker and Service Manager?
- **A)** REST API
- **B)** Open Service Broker API (OSB API)
- **C)** SOAP API
- **D)** GraphQL API

**Answer:**  
> **B) Open Service Broker API (OSB API)**

---

### 4. Where can you find SAP BTP services to be created or managed in the Kyma environment?
- **A)** SAP Discovery Center
- **B)** Kyma dashboard only
- **C)** Kubernetes API server
- **D)** SAP BTP Operator logs

**Answer:**  
> **A) SAP Discovery Center**

---

### 5. How can you access Service Management features in SAP BTP, Kyma runtime? (Choose two)
- **A)** Using the Kyma dashboard
- **B)** By listilng Deployments
- **C)** By checking the kubelet configuration
- **D)** Using Kubernetes-native tools like kubectl

**Answer:**  
> **A) Using the Kyma dashboard**  
> **D) Using Kubernetes-native tools like kubectl**

---

### 6. What is the role of the Service Manager in the SAP BTP Operator architecture?
- **A)** It manages and provisions SAP BTP services via the OSB API
- **B)** It deploys Pods
- **C)** It stores application logs
- **D)** It manages network policies

**Answer:**  
> **A) It manages and provisions SAP BTP services via the OSB API**

---

### 7. Which statement best describes observability in the context of microservice-based applications?
- **A)** The ability to automatically redeploy and scale Pods based on CPU usage
- **B)** The ability to gain insights into a system's internal state through logs, metrics, and traces
- **C)** The ability to deploy new services without downtime
- **D)** The ability to monitor only the external endpoints of an application

**Answer:**  
> **B) The ability to gain insights into a system's internal state through logs, metrics, and traces**

---

### 8. Which Kyma module provides APIs to collect and ship telemetry data to observability backends?
- **A)** Eventing module
- **B)** API Gateway module
- **C)** Serverless module
- **D)** Telemetry module

**Answer:**  
> **D) Telemetry module**

---

### 9. True or False: The LogPipeline API in the Kyma Telemetry module is used to collect and ship application logs to an observability backend.
- **A)** True
- **B)** False

**Answer:**  
> **A) True**

---

### 10. Which protocol is used by the Kyma Telemetry module for collecting and processing logs?
- **A)** SSH
- **B)** HTTP (Fluent Bit protocol)
- **C)** MQTT
- **D)** gRPC

**Answer:**  
> **B) HTTP (Fluent Bit protocol)**

---

### 11. True or False: The TracePipeline API in the Kyma Telemetry module is used to collect distributed traces from instrumented applications.
- **A)** True
- **B)** False

**Answer:**  
> **A) True**

---

### 12. Which protocol is supported by the TracePipeline and MetricPipeline for sending data to the gateway?
- **A)** SOAP
- **B)** FTP
- **C)** SMTP
- **D)** OpenTelemetry protocol (OTLP)

**Answer:**  
> **D) OpenTelemetry protocol (OTLP)**

---

### 13. What are the benefits of integrating Kyma Telemetry with SAP Cloud Logging? (Select 2)
- **A)** Instant access to logs, traces, and metrics for analysis and alerting
- **B)** Automatic scaling of the cluster
- **C)** Centralized observability for troubleshooting
- **D)** Management of user authentication

**Answer:**  
> **A) Instant access to logs, traces, and metrics for analysis and alerting**  
> **C) Centralized observability for troubleshooting**

---


### 14. What happens when the ServiceBinding for SAP Cloud Logging rotates credentials and updates the Secret?
- **A)** The cluster must be restarted
- **B)** The LogPipeline must be recreated manually
- **C)** The log agent is reconfigured with the new credentials automatically
- **D)** The logs are deleted

**Answer:**  
> **C) The log agent is reconfigured with the new credentials automatically**

---

### 15. What is the main reason for collecting application logs in Kyma?
- **A)** To monitor and troubleshoot applications by analyzing their behavior
- **B)** To automatically scale Pods
- **C)** To deploy new services
- **D)** To manage user authentication

**Answer:**  
> **A) To monitor and troubleshoot applications by analyzing their behavior**

---

### 16. When you deploy a sample application in Kyma, where are its logs written by default?
- **A)** To a PersistentVolume
- **B)** To stdout in the container
- **C)** To a ConfigMap
- **D)** To the SAP BTP cockpit

**Answer:**  
> **B) To stdout in the container**

---

### 17. What is the benefit of shipping logs from Kyma to SAP Cloud Logging?
- **A)** Logs are stored long-term and are searchable across Pods and namespaces
- **B)** Logs are deleted immediately after collection
- **C)** Logs are only available in the local Pod
- **D)** Logs are sent to the application developer by email

**Answer:**  
> **A) Logs are stored long-term and are searchable across Pods and namespaces**

---

### 18. Why is it important to enable credential rotation for a Service Binding to SAP Cloud Logging?
- **A)** It ensures credentials are updated regularly, reducing the risk of unauthorized access
- **B)** It deletes old logs from the SAP Cloud Logging backend
- **C)** It automatically restarts the Telemetry module
- **D)** It allows multiple users to share the same credentials indefinitely

**Answer:**  
> **A) It ensures credentials are updated regularly, reducing the risk of unauthorized access**

---

### 19. Does the Kyma Telemetry module store telemetry data?
- **A)** Yes, it brings Prometheus as an in-cluster backend.
- **B)** No, it supports you in collecting and shipping telemetry data to external backends.

**Answer:**  
> **B) No, it supports you in collecting and shipping telemetry data to external backends.**

---

### 20. What is the main purpose of a ConfigMap in Kubernetes?
- **A)** To store non-sensitive configuration data decoupled from application code
- **B)** To store sensitive data like passwords and API keys
- **C)** To manage network policies
- **D)** To scale Deployments

**Answer:**  
> **A) To store non-sensitive configuration data decoupled from application code**

---

### 21. What is the main purpose of a Secret in Kubernetes?
- **A)** To store application logs
- **B)** To deployment configurations
- **C)** To manage user authentication
- **D)** To store sensitive data such as passwords or API keys

**Answer:**  
> **D) To store sensitive data such as passwords or API keys**

---

### 22. Which of the following are recommended ways to use ConfigMaps and Secrets in your application? (Select 2)
- **A)** Inject them as environment variables
- **B)** Store them in plain text in version control
- **C)** Mount them as volumes
- **D)** Hard-code configuration values in the application source code

**Answer:**  
> **A) Inject them as environment variables**  
> **C) Mount them as volumes**

---

### 23. True or False: Mounting a ConfigMap or Secret makes the data available as files in a volume, while injecting makes the data available as environment variables in a Pod.
- **A)** True
- **B)** False

**Answer:**  
> **A) True**

---

### 24. Which command do you use to retrieve the logs via the label selector?
- **A)** kubectl logs -s
- **B)** kubectl logs -ls
- **C)** kubectl logs -l

**Answer:**  
> **C) kubectl logs -l**

---
