## Module 4 questions. Developing Applications on SAP BTP, Cloud Foundry runtime

---

### 1. Which of the following are benefits of using SAP BTP, Cloud Foundry runtime? (Choose 2)
- **A)** High availability with automatic routing and load balancing
- **B)** Only supports ABAP applications
- **C)** Managed security patching and updates
- **D)** Requires manual infrastructure management

**Answer:**  
> **A) High availability with automatic routing and load balancing**  
> **C) Managed security patching and updates**

---

### 2. Which of the following are key features of Cloud Foundry? (Choose 3)
- **A)** Developer productivity tools
- **B)** Container-based architecture
- **C)** On-premise only deployment
- **D)** Multilanguage support
- **E)** Manual scaling of applications only

**Answer:**  
> **A) Developer productivity tools**  
> **B) Container-based architecture**  
> **D) Multilanguage support**

---

### 3. What is the main function of the Routing Layer in Cloud Foundry?
- **A)** Managing user authentication
- **B)** Scheduling containers
- **C)** Aggregating logs and metrics
- **D)** Directing incoming client requests to the correct application instances

**Answer:**  
> **D) Directing incoming client requests to the correct application instances**

---

### 4. Which Cloud Foundry component is responsible for running applications in isolated containers and managing their lifecycle?
- **A)** UAA (User Account and Authentication)
- **B)** Diego (Container Runtime)
- **C)** Routing Layer
- **D)** Loggregator

**Answer:**  
> **B) Diego (Container Runtime)**

---

### 5. What is the role of UAA (User Account and Authentication) in Cloud Foundry?
- **A)** Managing application logs
- **B)** Handling user authentication and token generation
- **C)** Scheduling application containers
- **D)** Managing application routes

**Answer:**  
> **B) Handling user authentication and token generation**

---

### 6. Which component provides real-time logging and metrics for deployed applications in Cloud Foundry?
- **A)** Cloud Controller
- **B)** Loggregator
- **C)** Diego
- **D)** UAA

**Answer:**  
> **B) Loggregator**

---

### 7. What is a global account in SAP BTP?
- **A)** The highest-level account that contains subaccounts, entitlements, and manages overall resources
- **B)** An account for a single user only
- **C)** A type of Cloud Foundry service
- **D)** A database instance

**Answer:**  
> **A) The highest-level account that contains subaccounts, entitlements, and manages overall resources**

---

### 8. Which of the following can be managed at the global account level in SAP BTP? (Choose 2)
- **A)** Creating and managing subaccounts
- **B)** Assigning entitlements to subaccounts
- **C)** Deploying applications directly
- **D)** Managing application routes

**Answer:**  
> **A) Creating and managing subaccounts**  
> **B) Assigning entitlements to subaccounts**

---

### 9. What is NOT managed at the global account level in SAP BTP?
- **A)** Application deployment
- **B)** Entitlements
- **C)** Subaccount creation
- **D)** Region selection

**Answer:**  
> **A) Application deployment**

---

### 10. What is a subaccount in SAP BTP?
- **A)** A user’s personal account
- **B)** A container within a global account for resources, entitlements, and environments
- **C)** A type of Cloud Foundry service
- **D)** A database instance

**Answer:**  
> **B) A container within a global account for resources, entitlements, and environments**

---

### 11. What is a key feature of subaccounts in SAP BTP?
- **A)** Subaccounts can be assigned to specific regions
- **B)** Each subaccount can span multiple global accounts
- **C)** Subaccounts are only used for billing
- **D)** Subaccounts cannot have their own entitlements

**Answer:**  
> **A) Subaccounts can be assigned to specific regions**

---

### 12. Which of the following statements about subaccounts is correct?
- **A)** Subaccounts can contain multiple spaces and environments
- **B)** Subaccounts are the highest-level entity in SAP BTP
- **C)** Subaccounts are only for user management
- **D)** Subaccounts cannot be deleted

**Answer:**  
> **A) Subaccounts can contain multiple spaces and environments**

---

### 13. Which statement about spaces and organizations in Cloud Foundry is correct?
- **A)** Spaces are subdivisions within organizations
- **B)** Organizations are subdivisions within spaces
- **C)** Spaces and organizations are unrelated
- **D)** Each space can contain multiple organizations

**Answer:**  
> **A) Spaces are subdivisions within organizations**

---

### 14. What is a special feature of organizations in Cloud Foundry?
- **A)** Organizations provide a way to separate resources and users for different projects or teams
- **B)** Organizations can span multiple global accounts
- **C)** Organizations are only used for billing
- **D)** Organizations can only contain one space

**Answer:**  
> **A) Organizations provide a way to separate resources and users for different projects or teams**

---

### 15. Which of the following can be managed at the organization level in Cloud Foundry? (Choose 2)
- **A)** Assigning org-level roles (Org Manager, Org Auditor, Org User)
- **B)** Creating and managing spaces
- **C)** Setting quotas for memory and services for the entire organization
- **D)** Managing application logs

**Answer:**  
> **A) Assigning org-level roles (Org Manager, Org Auditor, Org User)**  
> **C) Setting quotas for memory and services for the entire organization**

---

### 16. Which of the following can be managed at the space level in Cloud Foundry? (Choose 2)
- **A)** Assigning user roles and permissions
- **B)** Creating global accounts
- **C)** Setting resource quotas for memory and services
- **D)** Managing SAP BTP entitlements

**Answer:**  
> **A) Assigning user roles and permissions**  
> **C) Setting resource quotas for memory and services**

---

### 17. What is a special feature of spaces in Cloud Foundry?
- **A)** Each space provides isolation for applications, services, and resources
- **B)** Spaces can span multiple organizations
- **C)** Spaces are only used for billing
- **D)** Spaces can only contain one application

**Answer:**  
> **A) Each space provides isolation for applications, services, and resources**

---

### 18. In Cloud Foundry, what is an application?
- **A)** A deployable unit of code that runs in a container and provides business functionality
- **B)** A user account
- **C)** A type of database
- **D)** A physical server

**Answer:**  
> **A) A deployable unit of code that runs in a container and provides business functionality**

---

### 19. Which of the following are special features of applications in Cloud Foundry? (Choose 2)
- **A)** Applications can be scaled horizontally by increasing the number of instances
- **B)** Applications must be written in Java only
- **C)** Applications can be bound to services such as databases or destinations
- **D)** Applications can only run in one space at a time

**Answer:**  
> **A) Applications can be scaled horizontally by increasing the number of instances**  
> **C) Applications can be bound to services such as databases or destinations**

---

### 20. What happens when you scale an application horizontally in Cloud Foundry?
- **A)** The application is moved to a different space
- **B)** More instances of the application are started to handle increased load
- **C)** The application is converted to a service
- **D)** The application is deleted

**Answer:**  
> **B) More instances of the application are started to handle increased load**

---

### 21. Which statement about application routes in Cloud Foundry is correct?
- **A)** Each application must have a unique route to be accessible
- **B)** Applications cannot share routes
- **C)** Routes are only used for internal communication
- **D)** Routes are not required for web applications

**Answer:**  
> **A) Each application must have a unique route to be accessible**

---

### 22. What is a buildpack in Cloud Foundry?
- **A)** A set of scripts that prepares your application for running by detecting the language, installing dependencies, and configuring the runtime environment
- **B)** A tool for managing user accounts
- **C)** A type of database
- **D)** A user role

**Answer:**  
> **A) A set of scripts that prepares your application for running by detecting the language, installing dependencies, and configuring the runtime environment**

---

### 23. What is a special feature of custom buildpacks in Cloud Foundry?
- **A)** They allow you to define your own runtime environment and dependencies for your application
- **B)** They can only be used for Java applications
- **C)** They are managed and updated by SAP
- **D)** They cannot be used in production

**Answer:**  
> **A) They allow you to define your own runtime environment and dependencies for your application**

---

### 24. How does Cloud Foundry determine which buildpack to use for an application if none is specified?
- **A)** It automatically detects and applies a suitable system buildpack
- **B)** It fails the deployment
- **C)** It uses the last used buildpack
- **D)** It prompts the user to choose

**Answer:**  
> **A) It automatically detects and applies a suitable system buildpack**

---

### 25. What is a service in Cloud Foundry?
- **A)** An external resource or functionality (such as a database, messaging, or authentication) that can be provisioned and bound to applications
- **B)** A user account
- **C)** A type of buildpack
- **D)** A physical server

**Answer:**  
> **A) An external resource or functionality (such as a database, messaging, or authentication) that can be provisioned and bound to applications**

---

### 26. Which of the following are special features of services in Cloud Foundry? (Choose 2)
- **A)** Services can be managed independently of applications
- **B)** Services must be deployed in the same space as the application
- **C)** Services can be bound to multiple applications
- **D)** Services can only be used by one application at a time

**Answer:**  
> **A) Services can be managed independently of applications**  
> **C) Services can be bound to multiple applications**

---

### 27. What is a service instance in Cloud Foundry?
- **A)** A specific, provisioned instance of a service that can be bound to one or more applications
- **B)** A running application
- **C)** A user role
- **D)** A type of buildpack

**Answer:**  
> **A) A specific, provisioned instance of a service that can be bound to one or more applications**

---

### 28. How do applications in Cloud Foundry typically access service credentials?
- **A)** Credentials are provided to the application via environment variables when the service is bound
- **B)** Credentials are hardcoded in the application code
- **C)** Credentials are sent by email
- **D)** Credentials are stored in the manifest.yml file

**Answer:**  
> **A) Credentials are provided to the application via environment variables when the service is bound**

---

### 29. In Cloud Foundry on SAP BTP, which term refers to the top-level container that groups spaces and users? Choose the correct answer.
- **A)** Organization
- **B)** Application
- **C)** Service
- **D)** Route

**Answer:**  
> **A) Organization**

---

### 30. Which of the following are types of services available in SAP BTP, Cloud Foundry Runtime? (Choose 2)
- **A)** Business services (e.g., SAP Document Management service)
- **B)** Technical services (e.g., SAP Application Autoscaler)
- **C)** User services
- **D)** Buildpack services

**Answer:**  
> **A) Business services (e.g., SAP Document Management service)**  
> **B) Technical services (e.g., SAP Application Autoscaler)**

---

### 31. What is the purpose of a service binding in Cloud Foundry?
- **A)** To connect an application to a service instance and provide configuration details via environment variables
- **B)** To create a new user account
- **C)** To deploy a new buildpack
- **D)** To scale an application

**Answer:**  
> **A) To connect an application to a service instance and provide configuration details via environment variables**

---

### 32. How can you create and bind a service instance to an application in SAP BTP, Cloud Foundry Runtime? (Choose 2)
- **A)** Using the SAP BTP cockpit
- **B)** Using the Cloud Foundry CLI
- **C)** By editing the application source code
- **D)** By sending an email to SAP support

**Answer:**  
> **A) Using the SAP BTP cockpit**  
> **B) Using the Cloud Foundry CLI**

---

### 33. What must you do if you add or change a service binding for a running application?
- **A)** Restart the application
- **B)** Restage the application so the new binding information is incorporated during staging
- **C)** Delete the application
- **D)** No action is required

**Answer:**  
> **B) Restage the application so the new binding information is incorporated during staging**

---

### 34. What is the main difference between a trial account and an enterprise account in SAP BTP?
- **A)** Trial accounts are for production use, enterprise accounts are for testing only
- **B)** Trial accounts are free and short-term, enterprise accounts are for long-term business needs and support productive environments
- **C)** Enterprise accounts do not support subaccounts
- **D)** Trial accounts have no technical limits

**Answer:**  
> **B) Trial accounts are free and short-term, enterprise accounts are for long-term business needs and support productive environments**

---

### 35. What is the purpose of entitlements in SAP BTP?
- **A)** To create new global accounts
- **B)** To assign user roles
- **C)** To define the rights to provision and consume specific SAP BTP services
- **D)** To store application logs

**Answer:**  
> **C) To define the rights to provision and consume specific SAP BTP services**

---

### 36. What is a quota in the context of SAP BTP, Cloud Foundry runtime?
- **A)** The number of users allowed in a subaccount
- **B)** The numeric limit on the consumption of a service plan within a global account or subaccount
- **C)** The number of applications that can be deployed in a space
- **D)** The number of buildpacks available

**Answer:**  
> **C) The numeric limit on the consumption of a service plan within a global account or subaccount**

---

### 37. How are entitlements and quotas managed in SAP BTP?
- **A)** By the SAP support team only
- **B)** Only at the subaccount level
- **C)** At the global account level, then distributed to subaccounts
- **D)** Only at the space level

**Answer:**  
> **C) At the global account level, then distributed to subaccounts**


---

### 39. What is the main purpose of the Cloud Foundry Command Line Interface (CF CLI)?
- **A)** To configure SAP Fiori launchpad
- **B)** To create user accounts
- **C)** To manage SAP HANA databases
- **D)** To deploy and manage applications, services, and resources in the Cloud Foundry runtime

**Answer:**  
> **D) To deploy and manage applications, services, and resources in the Cloud Foundry runtime**

---

### 40. What does the `cf api <your-api-endpoint>` command do?
- **A)** Deploys an application
- **B)** Sets the API endpoint for the CF CLI to connect to the correct Cloud Foundry environment
- **C)** Lists all available buildpacks
- **D)** Logs you into the Cloud Foundry CLI

**Answer:**  
> **B) Sets the API endpoint for the CF CLI to connect to the correct Cloud Foundry environment**

---

### 41. How can you log in to the CF CLI using single sign-on (SSO)?
- **A)** cf login -user
- **B)** cf login -api
- **C)** cf login -sso
- **D)** cf login --token

**Answer:**  
> **C) cf login -sso**

---

### 42. What is a benefit of using CF CLI plugins?
- **A)** They are only used for database management
- **B)** They allow you to extend the functionality of the CF CLI with additional commands, such as managing multitarget applications (MTAs)
- **C)** They are required for basic login
- **D)** They replace the need for the SAP BTP cockpit

**Answer:**  
> **B) They allow you to extend the functionality of the CF CLI with additional commands, such as managing multitarget applications (MTAs)**

---

### 43. What is the main purpose of the Open Service Broker API in Cloud Foundry?
- **A)** To provide a standardized way for platforms to provision, manage, and bind services to applications
- **B)** To manage user accounts
- **C)** To configure buildpacks
- **D)** To deploy applications

**Answer:**  
> **A) To provide a standardized way for platforms to provision, manage, and bind services to applications**

---

### 44. Which of the following actions can be performed using the Open Service Broker API? (Choose 2)
- **A)** Compiling application code
- **B)** Provisioning new service instances
- **C)** Creating user accounts
- **D)** Binding a service instance to an application

**Answer:**  
> **B) Provisioning new service instances**  
> **D) Binding a service instance to an application**

---

### 45. How does the Open Service Broker API benefit developers using SAP BTP, Cloud Foundry Runtime?
- **A)** It enables automated, consistent, and self-service provisioning and binding of services to applications
- **B)** It restricts the use of third-party services
- **C)** It is only used for internal SAP services
- **D)** It allows developers to manually configure all service connections

**Answer:**  
> **A) It enables automated, consistent, and self-service provisioning and binding of services to applications**


---

### 47. Which of the following statements about the deployment process using `cf push` in SAP BTP, Cloud Foundry Runtime is correct?
- **A)** The developer must always specify the buildpack to use, otherwise deployment fails.
- **B)** The application is deployed directly as a running container without any intermediate build or staging step.
- **C)** The buildpack automatically detects the application type and prepares the runtime environment, unless a Docker image is specified.
- **D)** The application URL must be manually configured after deployment.

**Answer:**  
> **C) The buildpack automatically detects the application type and prepares the runtime environment, unless a Docker image is specified.**

---

### 48. When deploying an application using the SAP BTP cockpit (web UI), which of the following is FALSE?
- **A)** You can upload either a compiled binary or a source code archive.
- **B)** You must always provide a `manifest.yml` file for the deployment to succeed.
- **C)** You can manually enter application details if you choose not to use a manifest.
- **D)** The deployment status is visually indicated in the cockpit interface.

**Answer:**  
> **B) You must always provide a `manifest.yml` file for the deployment to succeed.**

---

### 49. Which scenario best justifies using the Cloud MTA Build Tool (MBT) over Business Application Studio (BAS) or SAP Web IDE Full-Stack for deploying a multitarget application?
- **A)** You want a fully guided, wizard-based deployment experience.
- **B)** You need to integrate the build and deployment process into a custom CI/CD pipeline.
- **C)** You are deploying a single-component Node.js application.
- **D)** You want to avoid using any command-line tools.

**Answer:**  
> **B) You need to integrate the build and deployment process into a custom CI/CD pipeline.**

---

### 50. Which of the following is a key responsibility of the developer when deploying a Docker image to SAP BTP, Cloud Foundry Runtime, compared to using a buildpack?
- **A)** Using only images from the SAP Docker registry
- **B)** Ensuring the Docker image is kept up-to-date with security patches
- **C)** Selecting the correct buildpack for the application.
- **D)** Relying on SAP to manage all runtime dependencies.

**Answer:**  
> **B) Ensuring the Docker image is kept up-to-date with security patches**

---

### 51. Which statement best describes the difference between SAP Continuous Integration and Delivery (CI/CD) service and Project "Piper" for SAP BTP, Cloud Foundry Runtime?
- **A)** SAP CI/CD is suitable for standard deployment processes, while Project "Piper" is better for highly customized, complex workflows.
- **B)** Project "Piper" is a managed SAP service with predefined pipelines, while SAP CI/CD is open-source and requires manual setup.
- **C)** Both solutions require manual deployment to production.
- **D)** Only Project "Piper" supports integration with Git repositories.

**Answer:**  
> **A) SAP CI/CD is suitable for standard deployment processes, while Project "Piper" is better for highly customized, complex workflows.**

---

### 52. You are tasked with deploying a large-scale enterprise application with multiple microservices, each requiring different technologies and service dependencies. Which deployment approach is LEAST appropriate?
- **A)** Integrating deployment into a CI/CD pipeline using SAP CI/CD or Project "Piper".
- **B)** Deploying each component individually using `cf push` and managing dependencies manually.
- **C)** Packaging the application as an MTA and deploying with MBT or the MTA CF CLI plugin.
- **D)** Using Business Application Studio for a guided MTA deployment.

**Answer:**  
> **B) Deploying each component individually using `cf push` and managing dependencies manually.**

---

### 54. Which SAP BTP service provides a managed solution for setting up CI/CD pipelines with minimal configuration?
- **A)** SAP Cloud Connector
- **B)** SAP Continuous Integration and Delivery
- **C)** SAP HANA Cloud
- **D)** SAP Business Application Studio

**Answer:**  
> **B) SAP Continuous Integration and Delivery**

---

### 55. When configuring a CI/CD job in SAP Continuous Integration and Delivery, which of the following is required?
- **A)** A Docker image of your application
- **B)** A running SAP HANA instance
- **C)** A Git repository containing your project source code
- **D)** An SAP Fiori launchpad site

**Answer:**  
> **C) A Git repository containing your project source code**

---

### 56. In the context of SAP CI/CD, what is the function of a webhook?
- **A)** It deploys the application to production
- **B)** It manages user authentication
- **C)** It triggers a pipeline run automatically when changes are pushed to the repository
- **D)** It monitors application performance

**Answer:**  
> **C) It triggers a pipeline run automatically when changes are pushed to the repository**

---

### 57. Which of the following best describes a pipeline in SAP Continuous Integration and Delivery?
- **A)** A user management tool
- **B)** A set of manual deployment steps
- **C)** A sequence of automated tasks such as build, test, and deploy
- **D)** A type of SAP BTP subaccount

**Answer:**  
> **C) A sequence of automated tasks such as build, test, and deploy**

---

### 58. What must you do to allow SAP Continuous Integration and Delivery to access your source code repository?
- **A)** Deploy the repository as an application
- **B)** Configure repository credentials or a connection in the service
- **C)** Add the repository to the SAP BTP cockpit
- **D)** No action is required; access is automatic

**Answer:**  
> **B) Configure repository credentials or a connection in the service**

---

### 59. Which of the following is NOT a typical stage in a CI/CD pipeline as described in the SAP tutorial?
- **A)** Build
- **B)** Test
- **C)** Manual code review
- **D)** Deploy

**Answer:**  
> **C) Manual code review**

---

### 60. Which of the following best describes horizontal scaling in SAP BTP, Cloud Foundry Runtime?
- **A)** Increasing the disk quota for the application
- **B)** Increasing the memory allocated to each application instance
- **C)** Increasing the number of application instances to handle more load
- **D)** Upgrading the Cloud Foundry CLI

**Answer:**  
> **C) Increasing the number of application instances to handle more load**

---

### 61. What is the maximum memory you can allocate to a single application instance in SAP BTP, Cloud Foundry Runtime?
- **A)** 4 GB
- **B)** 8 GB
- **C)** 32 GB
- **D)** 16 GB

**Answer:**  
> **D) 16 GB**

---

### 62. Which of the following is NOT a limit imposed by SAP BTP, Cloud Foundry Runtime?
- **A)** Maximum disk quota per application instance
- **B)** Maximum number of users per space
- **C)** Maximum application package size
- **D)** Maximum number of instances per application (based on quota)

**Answer:**  
> **B) Maximum number of users per space**

---

### 63. How can administrators control the maximum resources available to applications in SAP BTP, Cloud Foundry Runtime?
- **A)** By editing the application source code
- **B)** By modifying the SAP BTP global account
- **C)** By setting quotas at the organization and space level
- **D)** By increasing the number of buildpacks

**Answer:**  
> **C) By setting quotas at the organization and space level**

---

### 64. What is the primary benefit of using the Application Autoscaler service in SAP BTP, Cloud Foundry Runtime?
- **A)** It increases the disk quota for all applications
- **B)** It dynamically adjusts the number of application instances based on real-time metrics
- **C)** It automatically updates application code
- **D)** It manages user authentication

**Answer:**  
> **B) It dynamically adjusts the number of application instances based on real-time metrics**

---

### 65. When using custom metrics for autoscaling in SAP BTP, Cloud Foundry Runtime, what is the recommended submission interval per application instance?
- **A)** Every 10 seconds
- **B)** Every 5 minutes
- **C)** Every 40 seconds
- **D)** Once per hour

**Answer:**  
> **C) Every 40 seconds**

---

### 66. What is the main purpose of built-in load balancing in SAP BTP, Cloud Foundry Runtime?
- **A)** To increase the memory of each application instance
- **B)** To manage user authentication
- **C)** To distribute incoming traffic evenly across all running instances of an application
- **D)** To deploy new buildpacks

**Answer:**  
> **C) To distribute incoming traffic evenly across all running instances of an application**

---

### 67. Which metric was used in the example scaling policy to trigger scaling actions?
- **A)** Disk usage
- **B)** CPU utilization
- **C)** Number of users
- **D)** Network bandwidth

**Answer:**  
> **B) CPU utilization**

---

### 68. What is the purpose of binding the Application Autoscaler service to an application?
- **A)** To enable the autoscaler to manage scaling for that application
- **B)** To deploy the application
- **C)** To update the application code
- **D)** To create a new Cloud Foundry space

**Answer:**  
> **A) To enable the autoscaler to manage scaling for that application**

---

### 69. How can you check the current number of running instances of your application in Cloud Foundry?
- **A)** cf scale <app-name>
- **B)** cf app <app-name>
- **C)** cf list-instances <app-name>
- **D)** cf show-instances

**Answer:**  
> **B) cf app <app-name>**

---

### 70. What should you do to clean up resources after testing the Application Autoscaler?
- **A)** Only stop the application
- **B)** Unbind and delete the autoscaler service instance, then delete the application
- **C)** Only delete the scaling policy file
- **D)** Restart the application

**Answer:**  
> **B) Unbind and delete the autoscaler service instance, then delete the application**

---

### 71. Why is zero downtime deployment (ZDD) important for modern applications?
- **A)** It reduces the need for application monitoring
- **B)** It ensures users have continuous access to applications during updates
- **C)** It eliminates the need for backups
- **D)** It allows for faster application development

**Answer:**  
> **B) It ensures users have continuous access to applications during updates**

---

### 72. Which statement about `cf push` and `cf deploy` is correct regarding zero downtime?
- **A)** Both commands guarantee zero downtime for all deployments
- **B)** `cf push` does not provide built-in zero downtime capabilities
- **C)** `cf deploy` is only used for single-component applications
- **D)** `cf push` is recommended for all production deployments

**Answer:**  
> **B) `cf push` does not provide built-in zero downtime capabilities**

---

### 73. What is a key benefit of using rolling deployment in Cloud Foundry?
- **A)** All instances are updated at once
- **B)** It allows gradual replacement of old instances with new ones, minimizing downtime
- **C)** It requires no additional configuration
- **D)** It is only suitable for stateful applications

**Answer:**  
> **B) It allows gradual replacement of old instances with new ones, minimizing downtime**

---

### 74. Which command enables rolling deployment in Cloud Foundry?
- **A)** cf push APP-NAME --strategy rolling
- **B)** cf deploy --rolling
- **C)** cf update --rolling
- **D)** cf scale --rolling

**Answer:**  
> **A) cf push APP-NAME --strategy rolling**

---

### 75. What is the main advantage of blue-green deployment?
- **A)** It requires fewer resources than other strategies
- **B)** It allows testing of the new version in a live-like environment before switching traffic
- **C)** It updates all users instantly without testing
- **D)** It is only used for database updates

**Answer:**  
> **B) It allows testing of the new version in a live-like environment before switching traffic**

---

### 76. Which command initiates a blue-green deployment for a multitarget application (MTA) in Cloud Foundry?
- **A)** cf push --strategy blue-green
- **B)** cf deploy <your-mta-archive> --strategy blue-green
- **C)** cf update --blue-green
- **D)** cf scale --blue-green

**Answer:**  
> **B) cf deploy <your-mta-archive> --strategy blue-green**

---

### 77. What is the purpose of a canary deployment?
- **A)** To update all users at once
- **B)** To gradually roll out a new version to a small subset of users for real-world testing
- **C)** To test only in a development environment
- **D)** To reduce the number of application instances

**Answer:**  
> **B) To gradually roll out a new version to a small subset of users for real-world testing**

---

### 78. Why is Redis used for session management in blue-green or rolling deployments with Approuter?
- **A)** To store application logs
- **B)** To ensure user sessions persist across application restarts or switches
- **C)** To manage application scaling
- **D)** To deploy new buildpacks

**Answer:**  
> **B) To ensure user sessions persist across application restarts or switches**

---

### 79. In a canary deployment, what happens if issues are detected in the new version during the initial rollout?
- **A)** The deployment is automatically completed for all users
- **B)** The new version can be quickly rolled back, limiting impact to only the canary group
- **C)** The application is deleted
- **D)** The old version is immediately removed

**Answer:**  
> **B) The new version can be quickly rolled back, limiting impact to only the canary group**

---

### 80. Which of the following is a primary benefit of canary deployment compared to blue-green deployment?
- **A)** It is only used for database migrations
- **B)** It updates all users at once
- **C)** It allows real-world testing with a subset of users before full rollout
- **D)** It requires no additional resources

**Answer:**  
> **C) It allows real-world testing with a subset of users before full rollout**

---

### 81. What is a potential challenge when using canary deployment for stateful applications?
- **A)** Reducing application memory usage
- **B)** Managing user authentication
- **C)** Increasing the number of application routes
- **D)** Ensuring data consistency and handling database schema changes

**Answer:**  
> **D) Ensuring data consistency and handling database schema changes**

---

### 82. During a canary deployment, how is traffic typically routed?
- **A)** Only internal users can access the new version
- **B)** All traffic is sent to the new version immediately
- **C)** Traffic is blocked until deployment is complete
- **D)** A small percentage of traffic is directed to the new version, while the majority continues to use the stable version

**Answer:**  
> **D) A small percentage of traffic is directed to the new version, while the majority continues to use the stable version**

---

### 83. Which scenario is best suited for a canary deployment strategy?
- **A)** Deploying static website content
- **B)** Migrating a database schema
- **C)** Deploying a critical update that must reach all users instantly
- **D)** Testing a new feature with a limited group of users to monitor for issues before a full rollout

**Answer:**  
> **D) Testing a new feature with a limited group of users to monitor for issues before a full rollout**

---

### 84. What is the main goal of a rolling app deployment in Cloud Foundry?
- **A)** To delete the old version before starting the new one
- **B)** To scale the application to zero before updating
- **C)** To update all application instances simultaneously
- **D)** To gradually replace old instances with new ones, ensuring some version is always available

**Answer:**  
> **D) To gradually replace old instances with new ones, ensuring some version is always available**

---

### 85. Which of the following is a potential drawback of rolling deployments?
- **A)** It cannot be automated
- **B)** It requires twice the resources of the application
- **C)** Rollbacks can be complex for stateful applications or database schema changes
- **D)** All users experience downtime

**Answer:**  
> **C) Rollbacks can be complex for stateful applications or database schema changes**

---

### 86. When using the `cf push APP-NAME --strategy rolling` command, what happens during the deployment?
- **A)** The application is deleted and redeployed
- **B)** The deployment fails if any users are connected
- **C)** All old instances are stopped before new ones are started
- **D)** New instances are started and old ones are stopped in phases, maintaining availability

**Answer:**  
> **D) New instances are started and old ones are stopped in phases, maintaining availability**

---

### 87. In which scenario is a rolling deployment most appropriate?
- **A)** When you need to test a new version with only a small subset of users
- **B)** When you want to minimize downtime but can tolerate some overlap between old and new versions
- **C)** When you need to instantly switch all users to a new version
- **D)** When you are deploying static content only

**Answer:**  
> **B) When you want to minimize downtime but can tolerate some overlap between old and new versions**

---

### 88. What is a key difference between rolling deployment and blue-green deployment?
- **A)** Blue-green deployment allows for full testing of the new version before switching traffic, while rolling deployment does not
- **B)** Rolling deployment requires two complete environments
- **C)** Blue-green deployment cannot be automated
- **D)** Rolling deployment is only for database updates

**Answer:**  
> **A) Blue-green deployment allows for full testing of the new version before switching traffic, while rolling deployment does not**

---

### 89. What is the primary goal of a blue-green deployment strategy in SAP BTP, Cloud Foundry Runtime?
- **A)** To minimize downtime and risk by running two environments (blue and green) and switching traffic only after testing the new version
- **B)** To update all application instances at once
- **C)** To reduce the number of application routes
- **D)** To delete the old version before deploying the new one

**Answer:**  
> **A) To minimize downtime and risk by running two environments (blue and green) and switching traffic only after testing the new version**

---

### 90. In a blue-green deployment, what does the "green" environment represent?
- **A)** The backup environment
- **B)** The new version of the application, deployed and tested before becoming live
- **C)** The current live production environment
- **D)** The database server

**Answer:**  
> **B) The new version of the application, deployed and tested before becoming live**

---

### 92. What is a key advantage of the blue-green deployment strategy when introducing breaking changes (such as a new required field) to an application?
- **A)** It requires fewer resources than other strategies
- **B)** It allows you to test the new version in isolation before switching all users to it
- **C)** It updates the database schema automatically
- **D)** It prevents the need for application testing

**Answer:**  
> **B) It allows you to test the new version in isolation before switching all users to it**

---

### 93. What happens to the old (blue) environment after the green environment becomes productive in a blue-green deployment?
- **A)** It is merged with the green environment
- **B)** It continues to serve traffic
- **C)** It is deleted or stopped to free up resources
- **D)** It is used for database backups

**Answer:**  
> **C) It is deleted or stopped to free up resources**

---

### 94. Which of the following is a best practice when performing a blue-green deployment?
- **A)** Thoroughly test the green environment before switching traffic
- **B)** Skip the testing phase to speed up deployment
- **C)** Immediately delete the blue environment before testing the green one
- **D)** Use the same route for both blue and green environments simultaneously

**Answer:**  
> **A) Thoroughly test the green environment before switching traffic**

---

### 95. What is the purpose of the "--strategy blue-green" option in the cf deploy command?
- **A)** It automates the blue-green deployment process, including route switching and cleanup
- **B)** It enables rolling deployment
- **C)** It updates the application without downtime but does not switch routes
- **D)** It is only used for canary deployments

**Answer:**  
> **A) It automates the blue-green deployment process, including route switching and cleanup**

---

### 96. In the context of SAP BTP, Cloud Foundry Runtime, which tool is commonly used to build multitarget application (MTA) archives for blue-green deployment?
- **A)** SAP Web IDE
- **B)** Cloud MTA Build Tool (mbt)
- **C)** SAP HANA Studio
- **D)** SAP Fiori Tools

**Answer:**  
> **B) Cloud MTA Build Tool (mbt)**

---

### 97. What is the main purpose of the `cf restart <app_name>` command in Cloud Foundry?
- **A)** To update the application code and dependencies
- **B)** To refresh the application's operational state without changing code or configuration
- **C)** To bind a new service to the application
- **D)** To permanently delete the application

**Answer:**  
> **B) To refresh the application's operational state without changing code or configuration**

---

### 98. How does `cf restart-app-instance <app_name> <instance_index>` differ from `cf restart <app_name>`?
- **A)** It restarts all instances of the application
- **B)** It restarts only the specified instance, minimizing impact on overall availability
- **C)** It updates the application code
- **D)** It deletes the application

**Answer:**  
> **B) It restarts only the specified instance, minimizing impact on overall availability**

---

### 99. When should you use the `cf restage <app_name>` command?
- **A)** When you have changed the application code
- **B)** When you have changed environment variables, bound a new service, or updated buildpacks/stacks
- **C)** When you want to stop the application
- **D)** When you want to scale the application

**Answer:**  
> **B) When you have changed environment variables, bound a new service, or updated buildpacks/stacks**

---

### 100. What is the difference between `cf restage` and `cf restart`?
- **A)** Both commands do exactly the same thing
- **B)** `cf restage` deletes the application
- **C)** `cf restage` recompiles the application with updated environment or dependencies, while `cf restart` simply restarts the app using the existing droplet
- **D)** `cf restart` updates the application code, while `cf restage` does not

**Answer:**  
> **C) `cf restage` recompiles the application with updated environment or dependencies, while `cf restart` simply restarts the app using the existing droplet**

---

### 102. What happens when an application instance crashes in Cloud Foundry?
- **A)** The application is deleted
- **B)** Cloud Foundry automatically attempts to restart the instance up to 200 times, with increasing wait times
- **C)** The instance is permanently stopped
- **D)** The application is restaged

**Answer:**  
> **B) Cloud Foundry automatically attempts to restart the instance up to 200 times, with increasing wait times**

---

### 103. What is the purpose of the evacuation process in Cloud Foundry?
- **A)** To scale the application
- **B)** To update environment variables
- **C)** To relocate application instances to new VMs during platform updates or VM replacements, ensuring continuity
- **D)** To delete old application versions

**Answer:**  
> **C) To relocate application instances to new VMs during platform updates or VM replacements, ensuring continuity**

---

### 104. How does a shutdown event differ from a crash event in Cloud Foundry?
- **A)** Both are the same
- **B)** Shutdown can be manual (e.g., `cf stop`) or automatic (e.g., failed health checks), while crash is always due to application failure
- **C)** Crash events never restart the application
- **D)** Shutdown is always manual, crash is always automatic

**Answer:**  
> **B) Shutdown can be manual (e.g., `cf stop`) or automatic (e.g., failed health checks), while crash is always due to application failure**

---

