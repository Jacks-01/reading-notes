## Reading Notes
## Assignment:

Statement: This topic is important because...
___

### Questions:
___

## Reading

[5 steps to RBAC](https://www.csoonline.com/article/3060780/security/5-steps-to-simple-role-based-access-control.html)

1.  What is Role Based Access Control (RBAC) and why do we care?
	- Assigning roles to certain users with differeing levels of access to the system. So if one person's password is compromised the whole system isn't.
2.  Describe a Role/Permission heirarchy that you might implement using RBAC.
	- having admins, and other roles to break up levels of authority. General use does not require access to the entire system.
1.  What approach might you take to implement RBAC?
	- assign roles
	- inventory systems
	- analyze workforce
	- never make one off changes
	- audit and make changes periodically

[wiki - RBAC](https://en.wikipedia.org/wiki/Role-based_access_control)

1.  If Authentication is “you are who you say you are,” what is Authorization?
	- can you do what you are asking to?
2.  Name three primary rules defined for RBAC.
	1.  Role assignment: A subject can exercise a permission only if the subject has selected or been assigned a role.
	2.  Role authorization: A subject's active role must be authorized for the subject. With rule 1 above, this rule ensures that users can take on only roles for which they are authorized.
	3.  Permission authorization: A subject can exercise a permission only if the permission is authorized for the subject's active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.
3.  Describe RBAC to a non-technical friend.
	- RBAC is a hierarchical way to  ensure saftey for systems. There are admins who can make system wide changes and infrastructure, and people who only need to enter data or view something for example.

## Videos

[RBAC tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA)

1.  What Are access rights Associated with? The User? or The Role? Explain.
	 - The role, because a role can be applied to multiple users but there is only one user. Otherwise you would have to grant every single person their own special rights which would be a lot of work.
2.  Access Rights, or Authorization, is activated after a user successfully does what?
	- verifies their identity
1.  Explain how RBAC might benefit a business.
	- less concern about security breaches
	- a more organized system since only authorized users can make changes



### Things I want to know more about:
___


### Sources (if any):
___
