
[*HOME*](https://nassir1976.github.io/reading-notes/)
## Readnote-10


## Reading: Event Driven Applications
### 1- Why is access control important?
- Access control is important because it is a valuable security technique that can be used to regulate who or what can view or use any given resource
- Access control models are responsible for granting or restricting access to resources. They depend on two things: user identification (verified by one or more authentication schemes) and feature authorization.

### 2- Describe an application that would need access control.
- Access control systems come in three variations: Discretionary Access Control (DAC), Managed Access Control (MAC), and Role-Based Access Control (RBAC).
### 3- What is a role used for?

- Role-based access control (RBAC) is a method of restricting network access based on the roles of individual users within an enterprise. RBAC lets employees have access rights only to the information they need to do their jobs and prevents them from accessing information that doesn't pertain to them.
- 4- Why is role based access control more scalable than discretionary or mandatory access control?
Role-based access control (RBAC). This is a widely used access control mechanism that restricts access to computer resources based on individuals or groups with defined business functions.

- The role-based security model relies on a complex structure of role assignments, role authorizations and role permissions developed using role engineering to regulate employee access to systems. RBAC systems can be used to enforce MAC

- Mandatory access control (MAC). This is a security model in which access rights are regulated by a central authority based on multiple levels of security. Often used in government and military environments, classifications are assigned to system resources and the operating system (OS) or security kernel. It grants or denies access to those resource objects based on the information security clearance of the user or device.

### Document the following Vocabulary Terms
 #### Term
 #### Authorization
- authorization is the process of verifying what they have access to. Initially we will just check token in the header of request for restricted routes, then allow or deny request
 #### Role Based Access Control
- Role-based access control (RBAC) is a method of restricting network access based on the roles of individual users within an enterprise. RBAC lets employees have access rights only to the information they need to do their jobs and prevents them from accessing information that doesn't pertain to them.
#### Capabilities 
- Are the abilities that the users can do according to their role.
 