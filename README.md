# Guru99 Software Testing Project:

## Testing the Banking Facility of Guru99 Bank

* The testing process consists of four main parts:
# 1. Requirement Gathering
This process is the initial phase of the project, and it involves converting the SRS document(Received from Guru99 ) into a table with all the modules and their functionalities associated with each of the two roles, in addition to the technical requirements and functional validations.

There are two main roles in the system:

### Manager role:
Has access to all the modules.

### Customer role: 
Accesses only some features of the system.
## System Chart:
Use Creately to create an overall system chart(From Guru99):
![Guru99 Banking Website System](https://github.com/user-attachments/assets/0b2f6857-bb9b-4e9e-9020-040b87cade07)

## 2. Unit Testing
Testing modules associated with the Manager role.

#000000 Test cases are in the file "TestCaseSuite".
#000000 This mainly focuses on validating each input field required in each module.
#000000 In the Project Objectives sent by Guru99, only some modules are required to be tested: 
- New Customer,
- Edit Customer,
- New Account,
- Edit Account,
- Delete Account,
- Delete Customer,
- Mini Statement,
- Customized Statement.
#000000 Other modules have their test cases written but have not been tested.
#000000 Test cases for the Customer role will be similar to those of the Manager role (not created yet).
#000000 Modules are only tested in the first two versions (v1 & v2)
