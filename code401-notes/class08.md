# Class 08

What is Role Based Access Control (RBAC) and why do we care?

- RBAC is a method of managing access to resources in a system based on roles. Each user is assigned one or more roles, and each role has certain permissions associated with it. We care about RBAC because it helps organizations manage access to sensitive information and resources more efficiently and securely.

Describe a Role/Permission hierarchy that you might implement using RBAC.

Role: Employee
Permissions: Read-only access to documents and files
Role: Manager
Permissions: Read and write access to documents, ability to approve or reject requests
Role: Administrator
Permissions: Full access to all resources, ability to create, delete, and modify user roles
What approach might you take to implement RBAC?
To implement RBAC, you would first identify the roles needed in your system, define the permissions for each role, and then assign users to roles based on their responsibilities and access needs. This can be done using RBAC frameworks or by custom implementation within the application code.

If Authentication is “you are who you say you are,” what is Authorization?

- Authorization is the process of determining what actions a user is allowed to perform after they have been authenticated. It involves checking the user's permissions and role assignments to ensure they have the necessary access rights to perform certain actions.

Name three primary rules defined for RBAC.

Role assignment: A user can be assigned one or more roles.
Role authorization: Users can access only the resources allowed by their role.
Permission authorization: Users can perform only the actions permitted by their role.
Describe RBAC to a non-technical friend.
RBAC is like assigning different roles to people in a play. Each role has its own script (permissions), determining what that character can do on stage. Just as actors follow their scripts, users in a system follow their roles' permissions to access certain parts of a system.

What Are access rights Associated with? The User? or The Role? Explain.

- Access rights are associated with the role. Users are assigned to roles, and each role has specific access rights or permissions associated with it. When a user assumes a role, they inherit the access rights associated with that role.

Access Rights, or Authorization, is activated after a user successfully does what?

- Access rights, or authorization, are activated after a user successfully authenticates or proves their identity to the system. Once authenticated, the system checks the user's permissions to determine what actions they are allowed to perform.

Explain how RBAC might benefit a business.

- RBAC can benefit a business by:

Simplifying access management: Roles streamline access control, reducing the complexity of managing individual permissions for each user.

- Enhancing security: RBAC ensures that users have only the necessary access rights, reducing the risk of unauthorized access to sensitive information.
Improving compliance: RBAC helps businesses enforce access policies and regulatory requirements by ensuring that users only have access to the resources they need to perform their job roles.
