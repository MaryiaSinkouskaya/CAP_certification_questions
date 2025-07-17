## Module 1 questions. SAP Cloud Application Programming Model Delta

---

### 1. When should you use event handlers in CAP applications?
- **A)** To deploy applications to Cloud Foundry
- **B)** Only for UI rendering
- **C)** To manage database connections
- **D)** To handle business logic and custom processing during service execution

**Answer:**
> **D) To handle business logic and custom processing during service execution**

---

### 2. What is the purpose of the `mta.yaml` file in an MTA development project?
- **A)** To define the structure and dependencies of a multi-target application
- **B)** To store user credentials
- **C)** To configure the SAP Fiori launchpad
- **D)** To manage database migrations

**Answer:**
> **A) To define the structure and dependencies of a multi-target application**

---

### 3. In Cloud Foundry, what is the difference between an organization and a space?
- **A)** Spaces are for authentication, organizations are for deployment
- **B)** Organizations group users and resources, spaces are subdivisions for project environments
- **C)** There is no difference
- **D)** Organizations are for user management, spaces are for billing

**Answer:**
> **B) Organizations group users and resources, spaces are subdivisions for project environments**

---

### 4. What is a necessary step to implement a custom error handler in the CAP SDK for Node.js?
- **A)** Register an "error" event handler on your service
- **B)** Modify the `package.json` file
- **C)** Change the database connection string
- **D)** Add a new entity to your CDS model

**Answer:**  
> **A) Register an "error" event handler on your service**

---

### 5. According to CAP best practices, which error types should you NOT catch in your custom handlers?
- **A)** Programming errors (e.g., syntax errors, out-of-memory)
- **B)** Business validation errors
- **C)** Data integrity errors
- **D)** User input errors

**Answer:**  
> **A) Programming errors (e.g., syntax errors, out-of-memory)**

---

### 6. When handling events in CAP, which of the following is NOT a valid event phase?
- **A)** before
- **B)** on
- **C)** after
- **D)** during

**Answer:**  
> **D) during**

---

### 7. What is the effect of registering multiple "before" handlers for the same event in CAP?
- **A)** Only the first handler is executed
- **B)** All handlers are executed in registration order
- **C)** Only the last handler is executed
- **D)** The application throws an error

**Answer:**  
> **B) All handlers are executed in registration order**

---

### 8. In CAP, what is the purpose of the `context.reject()` method in an event handler?
- **A)** To abort the current request and send an error to the client
- **B)** To approve the request
- **C)** To log a warning
- **D)** To restart the service

**Answer:**  
> **A) To abort the current request and send an error to the client**

---

### 9. Which of the following are advantages of using an MTA file for deployment? (Choose 2)
- **A)** It supports blue-green deployment
- **B)** It provides a build tool
- **C)** It stores user passwords
- **D)** It manages application dependencies

**Answer:**  
> **A) It supports blue-green deployment**  
> **B) It provides a build tool**

---

### 10. What is the purpose of the `mtad.yaml` file in an MTA project?
- **A)** To deploy an MTA application with system-specific details
- **B)** To develop and build an MTA application
- **C)** To archive an MTA application
- **D)** To store user credentials

**Answer:**  
> **A) To deploy an MTA application with system-specific details**

---

### 11. Which section in the `mta.yaml` file defines external services like databases or authentication services?
- **A)** modules
- **B)** resources
- **C)** parameters
- **D)** properties

**Answer:**  
> **B) resources**

---

### 12. What is the relationship between `mta.yaml` and `mtad.yaml` files?
- **A)** They are unrelated
- **B)** Both files are identical
- **C)** `mtad.yaml` is used for development, `mta.yaml` is for deployment
- **D)** `mta.yaml` is used for development, `mtad.yaml` is generated for deployment

**Answer:**  
> **D) `mta.yaml` is used for development, `mtad.yaml` is generated for deployment**

---

### 13. Which tool is commonly used to build and deploy MTA projects?
- **A)** mta build tool (`mbt`)
- **B)** npm
- **C)** Maven
- **D)** Gradle

**Answer:**  
> **A) mta build tool (`mbt`)**

---

### 14. In an MTA project, what does the `modules` section in the `mta.yaml` file define?
- **A)** External services
- **B)** User roles
- **C)** Application components to be built and deployed
- **D)** Database schemas

**Answer:**  
> **C) Application components to be built and deployed**

---

### 15. What is CQL in the context of CAP CDS?
- **A)** Core Query Language, an extension of SQL for querying CDS models
- **B)** Cloud Query Language, for cloud deployments
- **C)** Custom Query Language, for user-defined queries
- **D)** Common Query Language, for UI5 applications

**Answer:**  
> **A) Core Query Language, an extension of SQL for querying CDS models**

---

### 16. What is the purpose of the `@sap/cds/common` package in CAP?
- **A)** To provide advanced UI rendering for Fiori applications
- **B)** To enable deployment to multiple cloud platforms
- **C)** To manage user authentication and authorization
- **D)** To offer prebuilt types and aspects for reuse in CDS models

**Answer:**  
> **D) To offer prebuilt types and aspects for reuse in CDS models**

---

### 17. Which of the following best describes a CDS aspect?
- **A)** A special type of database view
- **B)** A configuration file for CAP deployment
- **C)** A tool for database migration
- **D)** A reusable set of properties and annotations that can be included in entities

**Answer:**  
> **D) A reusable set of properties and annotations that can be included in entities**

---

### 18. When adding a new service definition to your CAP project, where should you place the corresponding `.cds` file?
- **A)** In the `srv/` folder
- **B)** In the `db/` folder
- **C)** In the `app/` folder
- **D)** In the `config/` folder

**Answer:**  
> **A) In the `srv/` folder**

---

### 19. Which OData version is natively supported by CAP out of the box?
- **A)** OData V1
- **B)** OData V2
- **C)** OData V4
- **D)** OData V3

**Answer:**  
> **C) OData V4**

---

### 20. How can you expose a CDS entity as an OData service in CAP?
- **A)** By including the entity in a service definition in the `srv/` folder
- **B)** By adding the entity to the `db/` folder
- **C)** By adding a special annotation in the `package.json`
- **D)** By deploying to Cloud Foundry

**Answer:**  
> **A) By including the entity in a service definition in the `srv/` folder**

---

### 21. How does CAP handle deep reads and writes in OData services?
- **A)** They are not supported
- **B)** CAP supports deep reads and writes out of the box for related entities
- **C)** Only deep reads are supported, not writes
- **D)** Only deep writes are supported, not reads

**Answer:**  
> **B) CAP supports deep reads and writes out of the box for related entities**

---

### 22. You have already imported the aspect from the `@sap/cds/common` package (see code). Which is a valid way to extend the entity with the aspect?

```cds
using { cuid, managed } from '@sap/cds/common';
```

**A)**
```cds
entity Books : cuid, managed {
  title : String;
}
```

**B)**
```cds
entity Books {
  key ID : UUID;
  aspect managed;
  title : String;
}
```

**C)**
```cds
entity Books extends managed {
  title : String;
}
```

**D)**
```cds
entity Books {
  title : String;
} aspect managed;
```

**Answer:**
> **A)**

---
