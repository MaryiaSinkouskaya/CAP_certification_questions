## Module 3 questions. Developing Advanced Extensions with SAP Cloud SDK

---

### 1. Which of the following are key features of the software architecture of a side-by-side extension in the context of SAP S/4HANA Cloud? (Choose 2)
- **A)** The extension is decoupled from the SAP S/4HANA Cloud core application, and integration happens through APIs, events, and replication services.
- **B)** The extension's lifecycle is independent from the SAP application lifecycle.
- **C)** The extension is tightly coupled to the SAP S/4HANA Cloud core and must be updated together with it.
- **D)** The extension runs within the same application stack as SAP S/4HANA Cloud.

**Answer:**
> **A) The extension is decoupled from the SAP S/4HANA Cloud core application, and integration happens through APIs, events, and replication services.**  
> **B) The extension's lifecycle is independent from the SAP application lifecycle.**

---

### 2. Which of the following options are the main use cases to be covered using side-by-side extensibility? (Choose 2)
- **A)** Changing the colors of a standard UI.
- **B)** Creating a new UI for the existing application.
- **C)** Extending the existing application to include new functions.
- **D)** Changing the field's position in an existing screen.

**Answer:**  
> **B) Creating a new UI for the existing application.**  
> **C) Extending the existing application to include new functions.**

---

### 3. What is the main purpose of the SAP S/4HANA Virtual Data Model?
- **A)** To provide direct access to database tables
- **B)** To offer a business-oriented view of data
- **C)** To create custom user interfaces
- **D)** To manage user authorizations

**Answer:**  
> **B) To offer a business-oriented view of data**

---

### 4. Which technology is commonly used to expose the SAP S/4HANA Virtual Data Model?
- **A)** OData services
- **B)** FTP
- **C)** SOAP web services
- **D)** Email

**Answer:**  
> **A) OData services**

---

### 5. What does the Virtual Data Model (VDM) use to represent business objects?
- **A)** Database tables
- **B)** CDS views
- **C)** Excel files
- **D)** Java classes

**Answer:**  
> **B) CDS views**

---

### 6. Which of the following is a benefit of using the Virtual Data Model in SAP S/4HANA?
- **A)** It allows direct changes to the database schema
- **B)** It provides reusable, semantically rich data models
- **C)** It replaces all SAP Fiori apps
- **D)** It is only available for on-premise systems

**Answer:**  
> **B) It provides reusable, semantically rich data models**

---

### 7. Which of the following are advantages of using the OData Virtual Data Model (VDM) in the SAP Cloud SDK? (Choose 3)
- **A)** Lets you use common SQL queries
- **B)** Makes it easy to create, update, and delete data
- **C)** Checks that you use the right types for functions
- **D)** Helps you with auto-complete for names and properties
- **E)** Gives you ready-made database procedures

**Answer:**  
> **B) Makes it easy to create, update, and delete data**  
> **C) Checks that you use the right types for functions**  
> **D) Helps you with auto-complete for names and properties**

---

### 8. Which of the following are features of the SAP S/4HANA Virtual Data Model? (Choose 2)
- **A)** It shows how different entities are related.
- **B)** It lets you access database tables directly.
- **C)** It gives you a built-in UI to query tables.
- **D)** It enriches the entities with business semantics.

**Answer:**  
> **A) It shows how different entities are related.**  
> **D) It enriches the entities with business semantics.**

---

### 9. Why do custom extensions for SAP S/4HANA Cloud keep working even after SAP updates the system every quarter?
- **A)** The Virtual Data Model never changes.
- **B)** Extensions run only on SAP Business Technology Platform.
- **C)** SAP guarantees that public interfaces stay the same across updates.
- **D)** SAP fixes any problems with extensions through maintenance agreements.

**Answer:**  
> **C) SAP guarantees that public interfaces stay the same across updates.**

---

### 10. What is the main purpose of the SAP Cloud SDK?
- **A)** To design user interfaces for SAP Fiori
- **B)** To simplify the development of cloud applications that integrate with SAP solutions
- **C)** To manage SAP HANA database backups
- **D)** To create ABAP reports

**Answer:**  
> **B) To simplify the development of cloud applications that integrate with SAP solutions**

---

### 11. Which programming languages are supported by the SAP Cloud SDK?
- **A)** Only Java
- **B)** Only JavaScript/TypeScript
- **C)** Java and JavaScript/TypeScript
- **D)** Only Python

**Answer:**  
> **C) Java and JavaScript/TypeScript**

---

### 12. What feature does the SAP Cloud SDK provide for working with OData services?
- **A)** Virtual Data Model (VDM)
- **B)** SAP GUI scripting
- **C)** Database triggers
- **D)** SAP Fiori Elements

**Answer:**  
> **A) Virtual Data Model (VDM)**

---

### 13. Which of the following is a benefit of using the SAP Cloud SDK?
- **A)** Automatic generation of SAP Fiori apps
- **B)** Type-safe access to SAP APIs
- **C)** Direct modification of SAP S/4HANA core code
- **D)** Free SAP HANA database hosting

**Answer:**  
> **B) Type-safe access to SAP APIs**

---

### 14. The SAP Cloud SDK helps developers by:
- **A)** Providing tools for ABAP development only
- **B)** Offering libraries and tools for cloud-native application development
- **C)** Limiting access to SAP APIs
- **D)** Replacing SAP Business Technology Platform

**Answer:**  
> **B) Offering libraries and tools for cloud-native application development**

---

### 15. Which of the following are the technical features of the SAP Cloud SDK? (Choose 3)
- **A)** Resilience management
- **B)** Caching management
- **C)** Memory management
- **D)** Integration with SAP S/4HANA

**Answer:**  
> **A) Resilience management**  
> **B) Caching management**  
> **D) Integration with SAP S/4HANA**

---

### 16. Which of the following is a typical use case for the SAP Cloud SDK?
- **A)** Directly modifying SAP S/4HANA core code
- **B)** Consuming OData APIs from SAP S/4HANA in a cloud-native application
- **C)** Creating SAP GUI scripts
- **D)** Building SAP HANA database tables

**Answer:**  
> **B) Consuming OData APIs from SAP S/4HANA in a cloud-native application**

---

### 17. When would you use the SAP Cloud SDK’s Virtual Data Model (VDM)?
- **A)** When you want to write raw SQL queries against SAP HANA
- **B)** When you want type-safe, object-oriented access to SAP S/4HANA business data via OData
- **C)** When you need to design SAP Fiori Elements pages
- **D)** When you want to automate SAP GUI transactions

**Answer:**  
> **B) When you want type-safe, object-oriented access to SAP S/4HANA business data via OData**

---

### 18. Which scenario best fits the use of SAP Cloud SDK’s destination service?
- **A)** Storing user passwords
- **B)** Managing secure connections to multiple SAP systems from a cloud application
- **C)** Creating custom SAP Fiori apps
- **D)** Running ABAP code in the cloud

**Answer:**  
> **B) Managing secure connections to multiple SAP systems from a cloud application**

---

### 19. What does the `cf push` command do?
- **A)** Deletes an application
- **B)** Deploys an application to Cloud Foundry
- **C)** Lists all available services
- **D)** Logs out of Cloud Foundry

**Answer:**  
> **B) Deploys an application to Cloud Foundry**

---

### 20. Which command lists all applications in the current Cloud Foundry space?
- **A)** cf apps
- **B)** cf list
- **C)** cf show
- **D)** cf services

**Answer:**  
> **A) cf apps**

---

### 21. How do you view the logs of a running application using the CF CLI?
- **A)** cf show-logs
- **B)** cf logs <app-name>
- **C)** cf get-logs <app-name>
- **D)** cf app-logs <app-name>

**Answer:**  
> **B) cf logs <app-name>**

---

### 22. What is a buildpack in Cloud Foundry?
- **A)** A tool for managing user accounts
- **B)** A set of scripts that prepares your application for running on Cloud Foundry
- **C)** A database backup utility
- **D)** A command for scaling applications

**Answer:**  
> **B) A set of scripts that prepares your application for running on Cloud Foundry**

---

### 23. What does a buildpack typically do during the deployment process?
- **A)** Installs system updates
- **B)** Detects the application type, installs dependencies, and configures the runtime environment
- **C)** Deletes old application versions
- **D)** Changes user passwords

**Answer:**  
> **B) Detects the application type, installs dependencies, and configures the runtime environment**

---

### 24. How can you specify a custom buildpack when pushing an app with the CF CLI?
- **A)** cf push my-app --buildpack <buildpack-url>
- **B)** cf buildpack set my-app <buildpack-url>
- **C)** cf set-buildpack my-app <buildpack-url>
- **D)** cf push --custom-buildpack <buildpack-url>

**Answer:**  
> **A) cf push my-app --buildpack <buildpack-url>**

---

### 25. In Cloud Foundry, which attribute of an application reflects its original development language? Choose the correct answer.
- **A)** The Requested State.
- **B)** The Space.
- **C)** The Buildpack.
- **D)** The Route.

**Answer:**  
> **C) The Buildpack.**

---

### 26. What happens if no buildpack is specified when deploying an app?
- **A)** The deployment fails
- **B)** Cloud Foundry automatically detects and applies a suitable buildpack
- **C)** The app is deployed without dependencies
- **D)** The app is deployed as a static file

**Answer:**  
> **B) Cloud Foundry automatically detects and applies a suitable buildpack**

---

### 27. Which command would you use to deploy an MTA archive file (such as `myapp.mtar`) to Cloud Foundry?
- **A)** cf push myapp.mtar
- **B)** cf deploy myapp.mtar
- **C)** cf start myapp.mtar
- **D)** cf upload myapp.mtar

**Answer:**  
> **B) cf deploy myapp.mtar**

---

### 28. Which of the following statements is true?
- **A)** `cf push` is used for both single apps and MTA archives
- **B)** `cf deploy` is only for updating the Cloud Foundry CLI
- **C)** `cf push` is for single apps, while `cf deploy` is for MTA archives
- **D)** Both commands do exactly the same thing

**Answer:**  
> **C) `cf push` is for single apps, while `cf deploy` is for MTA archives**

---

### 29. In a typical SAP CAP Model application, when do you usually need to use the SAP Cloud SDK directly?
- **A)** When connecting to remote services using CAP’s built-in features
- **B)** When you need to perform custom logic, such as retrieving a JWT token from the request object
- **C)** When building Fiori UIs
- **D)** When writing ABAP code

**Answer:**  
> **B) When you need to perform custom logic, such as retrieving a JWT token from the request object**

---

### 30. Which scenario requires you to use the SAP Cloud SDK instead of the CAP Model?
- **A)** When building applications that use SAP HANA as the database
- **B)** When building applications with MongoDB or other databases not supported by CAP Model
- **C)** When using only standard SAP Fiori apps
- **D)** When deploying to SAP S/4HANA On-Premise

**Answer:**  
> **B) When building applications with MongoDB or other databases not supported by CAP Model**

---

### 31. If you have an existing Java application that was not built with the CAP Model, how can you add SAP integration features?
- **A)** Only by rewriting the application in CAP Model
- **B)** By using the SAP Cloud SDK tool set
- **C)** By using SAP GUI scripting
- **D)** By exporting data to Excel

**Answer:**  
> **B) By using the SAP Cloud SDK tool set**

---

### 32. Which of the following is a reason to use SAP Cloud SDK directly, even if you are using the CAP Model?
- **A)** To generate the Virtual Data Model (VDM) for custom or standard OData services
- **B)** To manage SAP Fiori launchpad tiles
- **C)** To create ABAP reports
- **D)** To update SAP HANA database schemas

**Answer:**  
> **A) To generate the Virtual Data Model (VDM) for custom or standard OData services**

---

### 33. What is the recommended approach for connecting to remote systems in a CAP application?
- **A)** Use SAP Cloud SDK directly for all connections
- **B)** Use CAP’s built-in connection features, which use SAP Cloud SDK behind the scenes
- **C)** Use only manual HTTP requests
- **D)** Use SAP GUI

**Answer:**  
> **B) Use CAP’s built-in connection features, which use SAP Cloud SDK behind the scenes**

---

### 34. How does the SAP Cloud Application Programming Model (CAP) use the SAP Cloud SDK?
- **A)** CAP uses the SAP Cloud SDK behind the scenes to connect to remote systems and manage technical details
- **B)** CAP and SAP Cloud SDK cannot be used together
- **C)** CAP replaces the SAP Cloud SDK for all integration tasks
- **D)** CAP only uses SAP Cloud SDK for user interface development

**Answer:**  
> **A) CAP uses the SAP Cloud SDK behind the scenes to connect to remote systems and manage technical details**

---

### 35. Where can you find APIs provided by SAP and SAP partners? Choose the correct answer.
- **A)** SAP API Business Hub
- **B)** SAP Business Application Studio
- **C)** SAP Cloud Connector

**Answer:**  
> **A) SAP API Business Hub**

---

### 36. What is the first step to try out the Business Partner API in the SAP Business Accelerator Hub?
- **A)** Retrieve your API key
- **B)** Log on to the SAP Business Accelerator Hub
- **C)** Install SAP Cloud Connector

**Answer:**  
> **B) Log on to the SAP Business Accelerator Hub**

---

### 37. Where can you retrieve your API key for testing APIs in the SAP Business Accelerator Hub?
- **A)** From the API documentation page on the SAP Business Accelerator Hub
- **B)** From SAP Business Application Studio
- **C)** From the SAP Cloud Connector

**Answer:**  
> **A) From the API documentation page on the SAP Business Accelerator Hub**

---

### 38. Which of the following tools is NOT strictly required to build a Java application with the SAP Cloud SDK if you are using SAP Business Application Studio?
- **A)** Java SE Development Kit (JDK)
- **B)** Apache Maven
- **C)** Git
- **D)** Cloud Foundry CLI
- **E)** Visual Studio Code

**Answer:**  
> **E) Visual Studio Code**

---

### 39. What is the main difference between the standard Cloud Foundry java_buildpack and the sap_java_buildpack?
- **A)** sap_java_buildpack only supports Tomcat, while java_buildpack supports TomEE
- **B)** sap_java_buildpack provides additional containers for TomEE and TomEE7
- **C)** java_buildpack is only for SAP BTP, while sap_java_buildpack is for any Cloud Foundry
- **D)** sap_java_buildpack does not support environment variables

**Answer:**  
> **B) sap_java_buildpack provides additional containers for TomEE and TomEE7**

---

### 40. When deploying a Java application to Cloud Foundry, which file is used to specify the buildpack, memory allocation, and environment variables?
- **A)** pom.xml
- **B)** manifest.yml
- **C)** application.properties
- **D)** build.gradle

**Answer:**  
> **B) manifest.yml**

---

### 41. Which Maven command will clean, build, and update all dependencies for a Java project?
- **A)** mvn build
- **B)** mvn install
- **C)** mvn clean install -U
- **D)** mvn update

**Answer:**  
> **C) mvn clean install -U**

---

### 42. What is the primary purpose of Apache TomEE in the context of SAP Cloud SDK for Java?
- **A)** It is a version control system
- **B)** It is a Java EE server combining Tomcat with Java EE features
- **C)** It is a build automation tool
- **D)** It is a SAP-specific IDE

**Answer:**  
> **B) It is a Java EE server combining Tomcat with Java EE features**

---

### 43. What is the first step to enable remote debugging for a Java application running in Cloud Foundry?
- **A)** Attach the debugger in your IDE
- **B)** Enable SSH for the application
- **C)** Set the required Java debug options using cf set-env
- **D)** Establish an SSH tunnel

**Answer:**  
> **C) Set the required Java debug options using cf set-env**

---

### 44. Which Cloud Foundry CLI command is used to enable SSH access for your application before remote debugging?
- **A)** cf enable-ssh <application name>
- **B)** cf ssh-keygen <application name>
- **C)** cf ssh <application name>
- **D)** cf restage <application name>

**Answer:**  
> **A) cf enable-ssh <application name>**

---

### 45. What is the purpose of establishing an SSH tunnel when remote debugging a Java application in Cloud Foundry?
- **A)** To upload new code to the application
- **B)** To forward the debug port from the application to your local machine
- **C)** To restart the application
- **D)** To update environment variables

**Answer:**  
> **B) To forward the debug port from the application to your local machine**

---

### 46. After enabling SSH and setting the debug options, what is the final step to start remote debugging in your IDE?
- **A)** Run mvn clean install
- **B)** Attach the debugger to the specified port
- **C)** Push the application again
- **D)** Set environment variables

**Answer:**  
> **B) Attach the debugger to the specified port**

---

### 47. What is the purpose of the `cf api YOUR_API_ENDPOINT_GOES_HERE` command?
- **A)** To set the Cloud Foundry API endpoint for your CLI session
- **B)** To deploy an application to Cloud Foundry
- **C)** To create a new Cloud Foundry space
- **D)** To list all available buildpacks

**Answer:**  
> **A) To set the Cloud Foundry API endpoint for your CLI session**

---

### 48. How can you verify which API endpoint is currently set in your Cloud Foundry CLI?
- **A)** By running `cf api`
- **B)** By running `cf info`
- **C)** By running `cf target`
- **D)** All of the above

**Answer:**  
> **D) All of the above**

---

### 49. Which of the following is NOT a resilience pattern provided by SAP Cloud SDK via Resilience4j?
- **A)** Circuit Breaker
- **B)** Bulkhead
- **C)** Timeout
- **D)** Data Encryption

**Answer:**  
> **D) Data Encryption**

---

### 50. What happens when a circuit breaker in SAP Cloud SDK switches to the OPEN state?
- **A)** All remote service calls are retried immediately
- **B)** No more remote service calls are made for a timeout period
- **C)** The application is restarted
- **D)** The cache is cleared

**Answer:**  
> **B) No more remote service calls are made for a timeout period**

---

### 51. In the Bulkhead pattern, what occurs if the number of concurrent requests exceeds the configured threshold?
- **A)** All requests are queued
- **B)** Further requests are automatically stopped until existing requests are completed
- **C)** The application crashes
- **D)** Requests are redirected to another service

**Answer:**  
> **B) Further requests are automatically stopped until existing requests are completed**

---

### 52. What is the purpose of a fallback function in SAP Cloud SDK’s resilience features?
- **A)** To retry failed requests indefinitely
- **B)** To provide an alternative result, such as cached data, when a remote service is unavailable
- **C)** To log errors only
- **D)** To increase the timeout duration

**Answer:**  
> **B) To provide an alternative result, such as cached data, when a remote service is unavailable**

---

### 53. Which of the following is NOT a recommended scenario for using caching in SAP Cloud SDK?
- **A)** When you expect specific data to be queried more than once
- **B)** When you want to reduce load on a remote server
- **C)** When you need to store more data than fits in RAM
- **D)** When you want to improve application responsiveness

**Answer:**  
> **C) When you need to store more data than fits in RAM**

---

### 54. What underlying technology does SAP Cloud SDK use for caching?
- **A)** Redis
- **B)** JCache
- **C)** Memcached
- **D)** File system

**Answer:**  
> **B) JCache**

---

### 55. Which statement about caching in SAP Cloud SDK is correct?
- **A)** Caching is not tenant-aware and should be avoided in multi-tenant applications
- **B)** SAP Cloud SDK handles tenant-aware caching automatically
- **C)** You must implement all caching logic manually
- **D)** Caching is only available for on-premise deployments

**Answer:**  
> **B) SAP Cloud SDK handles tenant-aware caching automatically**

---

### 56. What is the main purpose of using destinations in SAP BTP?
- **A)** To store user passwords
- **B)** To define and manage connections to remote systems and services
- **C)** To deploy applications to Cloud Foundry
- **D)** To create new SAP users

**Answer:**  
> **B) To define and manage connections to remote systems and services**

---

### 57. Why is it recommended to use destinations instead of hardcoding connection details in your application?
- **A)** Destinations are faster than hardcoded connections
- **B)** Destinations allow centralized, secure, and flexible management of connection details
- **C)** Hardcoding is required for multi-tenant applications
- **D)** Destinations are only used for database connections

**Answer:**  
> **B) Destinations allow centralized, secure, and flexible management of connection details**

---

### 58. Which of the following is a correct example of the `cf create-service destination` command?
- **A)** cf create-service destination lite my-destination
- **B)** cf create-service destination standard my-destination
- **C)** cf create-service destination free my-destination
- **D)** All of the above

**Answer:**  
> **D) All of the above**

---

### 59. After creating a destination service instance, what is the next step to use it in your application?
- **A)** Bind the destination service instance to your application
- **B)** Restart the Cloud Foundry CLI
- **C)** Delete the manifest.yml file
- **D)** Run cf push again

**Answer:**  
> **A) Bind the destination service instance to your application**

---

### 60. What is the main purpose of the `cf restage` command in Cloud Foundry?
- **A)** To restart an application
- **B)** To re-run the buildpack and stage the application again without changing the code
- **C)** To delete an application
- **D)** To update the application’s manifest file

**Answer:**  
> **B) To re-run the buildpack and stage the application again without changing the code**

---

### 61. What happens to your application when you run `cf restage`?
- **A)** The application is stopped, restaged, and then started again
- **B)** The application is deleted
- **C)** The application is scaled to zero instances
- **D)** The application’s logs are cleared

**Answer:**  
> **A) The application is stopped, restaged, and then started again**

---

### 62. When would you typically use the `cf restage` command?
- **A)** After changing environment variables or buildpack settings
- **B)** After pushing new code
- **C)** After deleting a service
- **D)** After scaling the application

**Answer:**  
> **A) After changing environment variables or buildpack settings**

---

### 63. Which of the following is a correct use case for `cf restage`?
- **A)** You updated a bound service’s credentials and want the app to pick up the changes
- **B)** You want to change the app’s route
- **C)** You want to delete the app
- **D)** You want to view the app’s logs

**Answer:**  
> **A) You updated a bound service’s credentials and want the app to pick up the changes**

---

### 64. What is the main purpose of the `package.json` file in a Node.js project?
- **A)** To store user credentials
- **B)** To define project metadata, dependencies, and scripts
- **C)** To configure the operating system
- **D)** To manage database connections

**Answer:**
> **B) To define project metadata, dependencies, and scripts**

---

### 65. If a file or directory is listed in `.cfignore`, what happens during `cf push`?
- **A)** It is uploaded to Cloud Foundry as usual
- **B)** It is excluded from the upload and not deployed
- **C)** It is deleted from your local project
- **D)** It is automatically added to the manifest.yml

**Answer:**
> **B) It is excluded from the upload and not deployed**

---

### 66. Which of the following files would you typically include in a `.cfignore` file?
- **A)** node_modules/
- **B)** .env
- **C)** test/
- **D)** All of the above

**Answer:**  
> **D) All of the above**

---

### 67. What is the main purpose of the `manifest.yml` file in a Cloud Foundry project?
- **A)** To define the structure and modules of a multi-target application
- **B)** To specify deployment settings for a single application
- **C)** To store user credentials
- **D)** To package multiple applications into a single archive

**Answer:**  
> **B) To specify deployment settings for a single application**

---

### 68. What does the `mta.yaml` file describe in an SAP MTA project?
- **A)** The deployment settings for a single app
- **B)** The structure, modules, and resources of a multi-target application
- **C)** The buildpack to use for deployment
- **D)** The application’s environment variables only

**Answer:**  
> **B) The structure, modules, and resources of a multi-target application**

---

### 69. What is an `.mtar` file in the context of SAP Cloud Foundry?
- **A)** A configuration file for a single app
- **B)** A YAML file for defining resources
- **C)** An archive that packages all modules and resources of an MTA for deployment
- **D)** A log file generated after deployment

**Answer:**  
> **C) An archive that packages all modules and resources of an MTA for deployment**

---

### 70. Which file is generated as a result of building an MTA project and is used for deployment with `cf deploy`?
- **A)** manifest.yml
- **B)** mta.yaml
- **C)** .mtar
- **D)** package.json

**Answer:**  
> **C) .mtar**

---

### 71. What does the `undeploy` command of the CF MTA plugin do?
- **A)** Deploys a new multi-target app
- **B)** Removes a multi-target app from Cloud Foundry
- **C)** Lists all multi-target apps
- **D)** Displays the health and status of an app

**Answer:**  
> **B) Removes a multi-target app from Cloud Foundry**

---

### 72. Which command lists all multi-target applications in your Cloud Foundry environment?
- **A)** mtas
- **B)** mta
- **C)** deploy
- **D)** bg-deploy

**Answer:**  
> **A) mtas**

---

### 73. What is the purpose of the `bg-deploy` command in the CF MTA plugin?
- **A)** To deploy a multi-target app using blue-green deployment
- **B)** To purge stale configuration entries
- **C)** To download operation logs
- **D)** To list active operations

**Answer:**  
> **A) To deploy a multi-target app using blue-green deployment**

---
### 74. What is the main purpose of the `mbt build` command?
- **A)** To deploy an application to Cloud Foundry
- **B)** To build a multi-target application (MTA) archive (.mtar file) from the project sources
- **C)** To start a Node.js application
- **D)** To create a new Cloud Foundry space

**Answer:**  
> **B) To build a multi-target application (MTA) archive (.mtar file) from the project sources**

---

### 75. What is the default output file generated by the `mbt build` command?
- **A)** manifest.yml
- **B)** mta.yaml
- **C)** .mtar file
- **D)** .zip file

**Answer:**  
> **C) .mtar file**

---

### 76. Which file must be present in your project directory to successfully run `mbt build`?
- **A)** package.json
- **B)** mta.yaml
- **C)** manifest.yml
- **D)** .cfignore

**Answer:**  
> **B) mta.yaml**

---

### 77. In the mta.yaml file, which statements are used to exchange configuration properties between modules? Choose the correct answer.
- **A)** Exports and imports.
- **B)** Sends and receives.
- **C)** Provides and requires.
- **D)** Pushes and pulls.

**Answer:**  
> **C) Provides and requires.**

---

### 78. Which CF MTA plugin command is used to deploy a new multi-target application or sync changes to an existing one?
- **A)** mta-ops
- **B)** deploy
- **C)** mtas
- **D)** undeploy

**Answer:**  
> **B) deploy**

---

### 79. What is the main responsibility of the application router in SAP BTP Cloud Foundry?
- **A)** Managing database connections
- **B)** Dispatching requests, handling authentication, and serving static content
- **C)** Compiling TypeScript code
- **D)** Running backend microservices

**Answer:**  
> **B) Dispatching requests, handling authentication, and serving static content**

---

### 80. Which npm module is commonly used to implement a custom application router in Node.js?
- **A)** @sap/xsenv
- **B)** @sap/approuter
- **C)** express
- **D)** @sap/cds

**Answer:**  
> **B) @sap/approuter**

---

### 81. What is the purpose of the `xs-app.json` file in an application router project?
- **A)** To define routes, authentication methods, and destinations
- **B)** To store user credentials
- **C)** To configure the database
- **D)** To specify npm dependencies

**Answer:**  
> **A) To define routes, authentication methods, and destinations**

---

### 82. What is the role of the XSUAA service in the authentication flow with the application router?
- **A)** It stores static files
- **B)** It issues a JWT after authenticating the user
- **C)** It manages database connections
- **D)** It compiles TypeScript code

**Answer:**  
> **B) It issues a JWT after authenticating the user**

---

### 83. How does the application router use the JWT after it is issued by XSUAA?
- **A)** It stores it in a database
- **B)** It adds the JWT to the request headers and forwards the request to the backend
- **C)** It ignores the JWT
- **D)** It sends the JWT to the user by email

**Answer:**  
> **B) It adds the JWT to the request headers and forwards the request to the backend**

---

### 84. What does resilience of SAP Cloud SDK help you to do in your application? (Choose 3)
- **A)** Automatically retry failed requests.
- **B)** Set timeouts.
- **C)** Protect downstream systems from overloading with circuit breakers.
- **D)** Correct errors in text input using dictionaries and syntax rules.
- **E)** Automatically fill default fields while creating a business object.

**Answer:**
> **A) Automatically retry failed requests.**  
> **B) Set timeouts.**  
> **C) Protect downstream systems from overloading with circuit breakers.**

---

