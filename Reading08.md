# Reading 08

## 5 steps to RBAC

What is Role Based Access Control (RBAC) and why do we care?
RBAC is the idea of assigning system access to users based on their role within an organization. The system needs of a given workforce are analyzed, with users grouped into roles based on common job responsibilities and system access needs. Access is then assigned to each person based strictly on their role assignment. With tight adherence to access requirements established for each role, access management becomes much easier. he question therefore is why, with an achievable and time-honored approach, we can’t seem to get a handle on access control. We are certainly being pushed in that direction of RBAC, with all of the major standards, including PCI DSS, HIPAA and Gramm-Leach-Bliley all requiring some form of it.

Describe a Role/Permission heirarchy that you might implement using RBAC.
RBAC greatly expand the effort required to create and maintain the necessary permissions.  RBAC arguably offers a more simplified and manageable approach, given that the privileges of a user in a given position are granted with a simple effort, to all others in the same role.  These methods can, however, be used in tandem to increase control.

What approach might you take to implement RBAC?

1. Inventory the systems
2. Analyze the workforce and create roles
3. Assign people to roles
4. Never make one-off changes
5. Audit- review the roles 

## wiki - RBAC

If Authentication is “you are who you say you are,” what is Authorization?
A subject can exercise a permission only if the permission is authorized for the subject's active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.

Name three primary rules defined for RBAC.

1. Role Assignment
2. Role authorization
3. Permission authorization

Describe RBAC to a non-technical friend.
Role-based access control is a policy-neutral access-control mechanism defined around roles and privileges. The components of RBAC such as role-permissions, user-role and role-role relationships make it simple to perform user assignments

## Videos/ RBAC tutorial

What Are access rights Associated with? The User? or The Role? Explain.
The role

Access Rights, or Authorization, is activated after a user successfully does what?
Have a role assigned to them

Explain how RBAC might benefit a business.
Policy does not need to be updated when a certain person with a roles leaves
New employees should be able to activate the desired role
Users in one role has access to a subset of the files and they can switch roles to gain access to other resources