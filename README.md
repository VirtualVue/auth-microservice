# auth-microservice

The Goal of this microservice is to Authenticate and Authorise, i.e deal with verifying the identity of a user, 
process or device often as a pre-requisite to allowing access to resources in an information system, and authorise 
by ensuring access is appropriately authorised.

The scope includes 
1. Single factor Authentication
2. Multi factor Authentication

Manage Permissions

1. Create permissions

Module specific special permissions
1. Search users
2. Change user password
3. Suspend user
4. Add user
5. Update user
6. Delete user

Manage Roles
1. Create roles
2. Update roles
3. Assign roles
4. Remove roles
5. Get Roles
6. Delete Roles

Manage Users
1. Create user
2. Validate user
3. Get user
4. Update user
5. Delete user
6. Suspend user
7. Change password
8. Forgot password
9. Search user



200 in case of success
403 in case of wrong creds/inappropriate
401 in case of failure