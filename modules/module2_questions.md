## Module 2 questions. Building Side-by-Side Extensions on SAP BTP

---

### 1. Which of the following are advantages of using an MTA file for deployment? (Choose 2)
- **A)** It supports blue-green deployment
- **B)** It provides a build tool
- **C)** It stores user passwords
- **D)** It manages application dependencies

**Answer:**  
> **A) It supports blue-green deployment**  
> **B) It provides a build tool**

---

### 2. What is a key difference between YAML and JSON?
- **A)** YAML is less human-readable than JSON
- **B)** JSON supports more data types than YAML
- **C)** YAML is a strict superset of JSON
- **D)** JSON allows comments, YAML does not

**Answer:**  
> **C) YAML is a strict superset of JSON**

---

### 3. Which of the following is a valid use case for YAML?
- **A)** Configuration files
- **B)** Log files
- **C)** Data serialization
- **D)** All of the above

**Answer:**  
> **D) All of the above**

---

### 4. Which of the following statements best describes the relationship between YAML and JSON?
- **A)** YAML is a subset of JSON
- **B)** Every JSON file is a valid YAML file
- **C)** JSON supports features not available in YAML
- **D)** YAML cannot represent arrays

**Answer:**  
> **B) Every JSON file is a valid YAML file**

---

### 5. Why might you choose YAML over JSON for configuration files?
- **A)** YAML is less human-readable than JSON
- **B)** YAML allows for more complex data structures and better readability
- **C)** JSON supports comments, YAML does not
- **D)** JSON is required for all cloud-native services

**Answer:**  
> **B) YAML allows for more complex data structures and better readability**

---

### 6. Which of the following is true regarding data migration from JSON to YAML?
- **A)** It is not possible to convert JSON to YAML
- **B)** JSON files must be rewritten entirely to become YAML
- **C)** JSON files can be used as valid YAML files without modification
- **D)** YAML files must be converted to JSON before use

**Answer:**  
> **C) JSON files can be used as valid YAML files without modification**

---

### 7. Which file extensions are commonly used for YAML files?
- **A)** .json
- **B)** .xml
- **C)** .yaml and .yml
- **D)** .txt

**Answer:**  
> **C) .yaml and .yml**

---

### 8. What is the main reason for using side-by-side extensibility in SAP S/4HANA Cloud environments?
- **A)** To modify the core SAP S/4HANA system directly
- **B)** To add custom business logic and UIs without changing the core system
- **C)** To upgrade the SAP S/4HANA system
- **D)** To manage user authorizations

**Answer:**  
> **B) To add custom business logic and UIs without changing the core system**

---

### 9. Which of the following is a best practice when extending SAP S/4HANA Cloud?
- **A)** Modify the core system directly
- **B)** Keep the core clean and use APIs for extensions
- **C)** Only use key-user extensibility for all requirements
- **D)** Avoid using SAP BTP for extensions

**Answer:**  
> **B) Keep the core clean and use APIs for extensions**

---

### 10. Which of the following runtimes are available for building non-ABAP-based extensions on SAP BTP? (Choose 2)
- **A)** SAP BTP, ABAP Environment
- **B)** SAP BTP, Cloud Foundry Runtime
- **C)** SAP BTP, Kyma Runtime
- **D)** SAP NetWeaver

**Answer:**  
> **B) SAP BTP, Cloud Foundry Runtime**  
> **C) SAP BTP, Kyma Runtime**

---

### 11. What is a "Fusion Team" in the context of SAP BTP extensibility?
- **A)** A team of only ABAP developers
- **B)** A team of only citizen developers
- **C)** A team where pro code and low-code developers collaborate
- **D)** A team focused on SAP S/4HANA upgrades

**Answer:**  
> **C) A team where pro code and low-code developers collaborate**

---

### 12. What is the purpose of the `cds init` command in the CAP CLI?
- **A)** To start the CAP server
- **B)** To initialize a new CAP project with the recommended folder structure
- **C)** To deploy the application to Cloud Foundry
- **D)** To generate OData services from an existing database

**Answer:**  
> **B) To initialize a new CAP project with the recommended folder structure**

---

### 13. What is the primary function of the `cds watch` command in the CAP CLI (Node.js runtime)?
- **A)** To deploy the project to SAP BTP
- **B)** To continuously monitor project files and automatically restart the Node.js CAP server on changes
- **C)** To generate database migrations
- **D)** To build the MTA archive

**Answer:**  
> **B) To continuously monitor project files and automatically restart the Node.js CAP server on changes**

_Tip: For CAP Java applications, you can use `mvn cds:watch` instead._

---

### 14. What is typically stored in the `db/data` folder of a CAP project?
- **A)** Source code for services
- **B)** Sample data in CSV or JSON format for database initialization
- **C)** UI5 application files
- **D)** CAP configuration files

**Answer:**  
> **B) Sample data in CSV or JSON format for database initialization**

---

### 15. What is the main purpose of the `db` folder in a CAP project?
- **A)** To store service implementation files
- **B)** To define the data model and provide database-related artifacts
- **C)** To store deployment scripts
- **D)** To manage user authentication

**Answer:**  
> **B) To define the data model and provide database-related artifacts**

---

### 16. What is typically defined in the `schema.cds` file in the `db` folder?
- **A)** Service definitions
- **B)** Data model entities, types, and associations
- **C)** UI annotations
- **D)** Application configuration

**Answer:**  
> **B) Data model entities, types, and associations**

---

### 17. What is the primary purpose of the `package.json` file in a CAP project?
- **A)** To define the project's dependencies and scripts
- **B)** To store database data
- **C)** To configure SAP Fiori launchpad
- **D)** To define data models

**Answer:**  
> **A) To define the project's dependencies and scripts**

---

### 18. Which of the following information is typically found in the `package.json` file of a CAP project?
- **A)** Project name and version
- **B)** List of npm dependencies
- **C)** Custom scripts for build and start
- **D)** All of the above

**Answer:**  
> **D) All of the above**

---

### 19. In a CAP project, which command uses the information in `package.json` to install dependencies?
- **A)** cds build
- **B)** npm install
- **C)** cds deploy
- **D)** cds watch

**Answer:**  
> **B) npm install**

---

### 20. Which folder should SAP Fiori apps be placed in within a CAP project?
- **A)** db
- **B)** srv
- **C)** app
- **D)** config

**Answer:**  
> **C) app**

---

### 21. What is a key feature of CAP regarding SAP Fiori elements UIs?
- **A)** CAP only supports React UIs
- **B)** CAP provides out-of-the-box support for SAP Fiori elements, including annotations and draft features
- **C)** CAP does not support any UI integration
- **D)** CAP only supports static HTML pages

**Answer:**  
> **B) CAP provides out-of-the-box support for SAP Fiori elements, including annotations and draft features**

---

### 22. What is the purpose of the SAP Fiori Tools Page Map Editor?
- **A)** To manage database migrations
- **B)** To visually design and edit SAP Fiori pages, generating annotation files
- **C)** To deploy CAP projects to Cloud Foundry
- **D)** To monitor application logs

**Answer:**  
> **B) To visually design and edit SAP Fiori pages, generating annotation files**


---


### 23. Which of the following is true about the effect of `@requires` on access control?
- **A)** It grants access to all users by default
- **B)** It revokes default access and only grants access to specified roles
- **C)** It only affects database migrations
- **D)** It is ignored by the CAP runtime

**Answer:**  
> **B) It revokes default access and only grants access to specified roles**

---

### 24. Which of the following statements about UI frameworks and CAP is correct?
- **A)** Only SAP Fiori elements can consume CAP services
- **B)** CAP services can be consumed by any UI framework using standard AJAX requests
- **C)** CAP only supports SAP UI5
- **D)** CAP does not support frontend integration

**Answer:**  
> **B) CAP services can be consumed by any UI framework using standard AJAX requests**

---

### 25. What is the main benefit of using SAP Fiori Tools in SAP Business Application Studio or VS Code?
- **A)** They provide advanced productivity tools for designing and adding SAP Fiori apps to CAP projects
- **B)** They are required to run CAP projects
- **C)** They replace the need for OData services
- **D)** They are only used for backend development

**Answer:**  
> **A) They provide advanced productivity tools for designing and adding SAP Fiori apps to CAP projects**

---

### 26. What is the purpose of the draft feature in SAP Fiori elements UIs with CAP?
- **A)** To enable offline access to the application
- **B)** To prevent data loss and support concurrent editing by multiple users
- **C)** To generate database migrations
- **D)** To deploy the application to Cloud Foundry

**Answer:**  
> **B) To prevent data loss and support concurrent editing by multiple users**

---

### 27. What are some characteristics of CAP event handling? (Choose 2)
- **A)** You can register event handlers with instances of cds.service to add custom logic.
- **B)** You can register only one event handler for a specific event.
- **C)** You can register multiple event handlers for each event phase.
- **D)** You must use the handler registration API srv.emit(<event>) to de-register event handlers.

**Answer:**  
> **A) You can register event handlers with instances of cds.service to add custom logic.**  
> **C) You can register multiple event handlers for each event phase.**


---

### 28. What is the purpose of the `@requires` annotation in a CAP CDS model?
- **A)** To define database indexes
- **B)** To restrict access to entities or services based on user roles
- **C)** To specify data types
- **D)** To generate OData services

**Answer:**  
> **B) To restrict access to entities or services based on user roles**

---

### 29. Where can the `@requires` annotation be applied in a CAP project?
- **A)** Only on the entire project
- **B)** On services and entities
- **C)** Only on database tables
- **D)** Only on UI components

**Answer:**  
> **B) On services and entities**

---


### 30. What is a scope in the context of XSUAA?
- **A)** A user account
- **B)** An application deployment
- **C)** An authorization or access right in an application or service
- **D)** A database table

**Answer:**  
> **C) An authorization or access right in an application or service**

---

### 31. What is the function of the xs-security.json file in a CAP project?
- **A)** It defines the application's security configuration, including xsappname, scopes, and role templates
- **B)** It stores user passwords
- **C)** It contains UI annotations
- **D)** It manages database migrations

**Answer:**  
> **A) It defines the application's security configuration, including xsappname, scopes, and role templates**

---

### 32. In xs-security.json, what does the "scopes" section define?
- **A)** The application's database tables
- **B)** The permissions or access rights that can be granted
- **C)** The list of users
- **D)** The UI layout

**Answer:**  
> **B) The permissions or access rights that can be granted**

---

### 33. In xs-security.json, what is a "role-template"?
- **A)** A template for creating new users
- **B)** A definition that groups scopes into roles that can be assigned to users
- **C)** A database migration script
- **D)** A UI component

**Answer:**  
> **B) A definition that groups scopes into roles that can be assigned to users**

---

### 34. Which of the following is the correct form for using the `@restrict` annotation in a CDS model?
- **A)** `@restrict: 'admin'`
- **B)** `@restrict: [ { grant: 'READ', to: 'admin' } ]`
- **C)** `@restrict: { grant: 'READ', to: 'admin' }`
- **D)** `@restrict: [ 'admin' ]`

**Answer:**  
> **B) @restrict: [ { grant: 'READ', to: 'admin' } ]**

---

### 35. What is the effect of the following annotation in a CAP model?
```cds
@restrict: [
  { grant: 'READ', to: 'admin' },
  { grant: 'READ', where: 'buyer = $user' }
]
entity Orders { ... }
```
- **A)** Only users with the 'admin' role or users who are the buyer can read Orders
- **B)** All users can read Orders
- **C)** Only the admin can update Orders
- **D)** The Orders entity is hidden from all users

**Answer:**  
> **A) Only users with the 'admin' role or users who are the buyer can read Orders**

---

### 36. Which command starts the mock server locally for API_BUSINESS_PARTNER?
- **A)** API_BUSINESS_PARTNER cds mock
- **B)** cds API_BUSINESS_PARTNER mock
- **C)** cds mock API_BUSINESS_PARTNER

**Answer:**  
> **C) cds mock API_BUSINESS_PARTNER**

---

### 37. What is multitenancy in the context of a CAP application?
- **A)** Running multiple CAP projects on one server
- **B)** Allowing multiple customers (tenants) to use the same application instance with data isolation
- **C)** Deploying to multiple cloud platforms
- **D)** Using multiple databases in one project

**Answer:**  
> **B) Allowing multiple customers (tenants) to use the same application instance with data isolation**

---

### 38. Which library provides built-in support for multitenancy in CAP applications?
- **A)** @sap/cds-dk
- **B)** @sap/cds-mtxs
- **C)** @sap/cds-odata
- **D)** @sap/cds-hana

**Answer:**  
> **B) @sap/cds-mtxs**

---

### 39. What is the purpose of the `cds build` command in a CAP project?
- **A)** To deploy the application to SAP BTP
- **B)** To execute build tasks and prepare the project for deployment
- **C)** To start the CAP server
- **D)** To install project dependencies

**Answer:**  
> **B) To execute build tasks and prepare the project for deployment**

---


### 40. In the context of SAP BTP, what is a role collection?
- **A)** A group of users
- **B)** A set of roles that can be assigned to a user
- **C)** A list of applications
- **D)** A type of database schema

**Answer:**  
> **B) A set of roles that can be assigned to a user**

---

### 41. Which SAP BTP environments can you deploy a CAP application to? (Choose 2)
- **A)** SAP BTP, Cloud Foundry Runtime
- **B)** SAP BTP, Kyma Runtime
- **C)** SAP NetWeaver
- **D)** SAP ECC

**Answer:**  
> **A) SAP BTP, Cloud Foundry Runtime**  
> **B) SAP BTP, Kyma Runtime**

---

### 42. What is the recommended entry point for multitenant CAP applications on SAP BTP?
- **A)** Direct database access
- **B)** Standalone App Router
- **C)** SAP Web IDE
- **D)** SAP Fiori Launchpad

**Answer:**  
> **B) Standalone App Router**

---

### 43. What is the purpose of the mta.yaml file in a CAP project?
- **A)** To define the structure, modules, resources, and configuration for deployment as a multitarget application
- **B)** To store user credentials
- **C)** To manage database migrations
- **D)** To define UI annotations

**Answer:**  
> **A) To define the structure, modules, resources, and configuration for deployment as a multitarget application**


---

### 44. What is the function of the App Router in a CAP deployment?
- **A)** It manages authentication and routes requests to backend services
- **B)** It stores application data
- **C)** It generates OData services
- **D)** It builds the MTA archive

**Answer:**  
> **A) It manages authentication and routes requests to backend services**

---

### 45. What is the result of running `mbt build` in a CAP project?
- **A)** It starts the CAP server
- **B)** It creates an MTA archive (MTAR) for deployment
- **C)** It installs project dependencies
- **D)** It generates UI annotations

**Answer:**  
> **B) It creates an MTA archive (MTAR) for deployment**

---

### 46. What is the purpose of the extension descriptor (mtaext.yaml) in the MTA deployment process?
- **A)** To override or augment the deployment descriptor with environment-specific settings
- **B)** To define database tables
- **C)** To store user passwords
- **D)** To generate OData services

**Answer:**  
> **A) To override or augment the deployment descriptor with environment-specific settings**


---

### 47. In the context of MTA, what is a "module"?
- **A)** A user account
- **B)** A subcomponent of the application, such as a database, service, or UI, developed with a specific technology
- **C)** A deployment script
- **D)** A configuration file

**Answer:**  
> **B) A subcomponent of the application, such as a database, service, or UI, developed with a specific technology**

---

### 48. What is the purpose of the MTA archive (MTAR) file in lifecycle management?
- **A)** It stores user credentials
- **B)** It is a single deployable package containing all modules and descriptors for the application
- **C)** It is used for database migrations only
- **D)** It contains only UI resources

**Answer:**  
> **B) It is a single deployable package containing all modules and descriptors for the application**

---

### 49. What are the aspects of a Multi-Target Application (MTA) model in the lifecycle management of distributed applications? (Choose 3)
- **A)** Composition
- **B)** CI/CD
- **C)** Configuration
- **D)** Integration
- **E)** Dependencies

**Answer:**  
> **A) Composition**  
> **C) Configuration**  
> **E) Dependencies**

---


### 50. A development space is automatically created for you when you enable the SAP BTP, Cloud Foundry runtime in your subaccount.
- **A)** True
- **B)** False

**Answer:**  
> **B) False**

---

### 51. What is blue-green deployment?
- **A)** Deploying to two different cloud providers at the same time
- **B)** A deployment strategy where a new version (green) is deployed alongside the old version (blue), and traffic is switched after successful testing
- **C)** Deploying only to development environments
- **D)** A method for database migration

**Answer:**  
> **B) A deployment strategy where a new version (green) is deployed alongside the old version (blue), and traffic is switched after successful testing**

---

### 52. Which file holds the SAP Authorization and Trust Management service security configuration for the INCIDENT-MANAGEMENT project?
- **A)** xs-security.json
- **B)** package.json
- **C)** manifest.json

**Answer:**  
> **A) xs-security.json**

---


### 53. In the context of SAP BTP, which tool or approach supports blue-green deployment for CAP applications?
- **A)** Manual file copying
- **B)** MTA (Multi-Target Application) deployment with Cloud Foundry
- **C)** Editing the database directly
- **D)** Using only the SAP Fiori tools

**Answer:**  
> **B) MTA (Multi-Target Application) deployment with Cloud Foundry**

---

### 54. In blue-green deployment, both the old and new versions of the application are running at the same time during the switch.
- **A)** True
- **B)** False

**Answer:**  
> **A) True**

---

### 55. Blue-green deployment helps to minimize downtime during application updates.
- **A)** True
- **B)** False

**Answer:**  
> **A) True**

---

### 56. Blue-green deployment is only possible when using manual file copying.
- **A)** True
- **B)** False

**Answer:**  
> **B) False**

---


### 57. What is the primary purpose of the `cds compile` command in a CAP project?
- **A)** To start the CAP development server
- **B)** To generate database-specific artifacts (e.g., SQL, EDMX) from CDS models
- **C)** To deploy the application to Cloud Foundry
- **D)** To install project dependencies

**Answer:**
> **B) To generate database-specific artifacts (e.g., SQL, EDMX) from CDS models**

---

### 58. What is the main purpose of the `cds add pipeline` command in a CAP project?
- **A)** To add CI/CD pipeline configuration files to your project
- **B)** To start the CAP development server
- **C)** To deploy the application to SAP BTP
- **D)** To generate database artifacts

**Answer:**
> **A) To add CI/CD pipeline configuration files to your project**

---

### 59. After running `cds add pipeline` in your CAP project, which of the following files or folders are typically created? (Choose 2)
- **A)** `.pipeline/` directory with pipeline configuration
- **B)** `package.json` file
- **C)** `.github/workflows/` directory
- **D)** Jenkinsfile or similar pipeline descriptor

**Answer:**
> **A) `.pipeline/` directory with pipeline configuration**  
> **D) Jenkinsfile or similar pipeline descriptor**

---

### 60. Which scenario best justifies using the `cds add pipeline` command in a CAP project?
- **A)** You want to enable automated build and deployment processes for your project
- **B)** You want to add a new database entity
- **C)** You want to generate OData services
- **D)** You want to update project dependencies

**Answer:**
> **A) You want to enable automated build and deployment processes for your project**

---

### 61. What is the general purpose of the `cds add` command in a CAP project?
- **A)** To add features, modules, or capabilities to your project (such as samples, pipeline, or hana)
- **B)** To start the CAP development server
- **C)** To deploy the application to SAP BTP
- **D)** To remove unused dependencies

**Answer:**
> **A) To add features, modules, or capabilities to your project (such as samples, pipeline, or hana)**

---

### 62. Which of the following are valid options you can use with the `cds add` command? (Choose 2)
- **A)** `cds add hana`
- **B)** `cds add pipeline`
- **C)** `cds add deployer`
- **D)** `cds add remove`

**Answer:**
> **A) `cds add hana`**  
> **B) `cds add pipeline`**

---

### 63. Which scenario best justifies using the `cds add hana` command in a CAP project?
- **A)** You want to enable SAP HANA-specific features and deployment for your project
- **B)** You want to add a new UI module
- **C)** You want to update project dependencies
- **D)** You want to remove the database module

**Answer:**
> **A) You want to enable SAP HANA-specific features and deployment for your project**

---
