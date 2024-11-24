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

- Test cases are in the file "TestCaseSuite".
- This mainly focuses on validating each input field required in each module.
- In the Project Objectives sent by Guru99, only some modules are required to be tested: 
   1. New Customer,
   2. Edit Customer,
   3. New Account,
   4. Edit Account,
   5. Delete Account,
   6. Delete Customer,
   7. Mini Statement,
   8. Customized Statement.
- Other modules have their test cases written but have not been tested.
- Test cases for the Customer role will be similar to those of the Manager role (not created yet).
- Modules are only tested in the first two versions (v1 & v2)
## 3. Integration Testing
- Testing the integration of the modules and verifying their functionalities.

- This is done for these modules associated with the Manager role: 
  1. New Customer,
  2. Edit Customer,
  3. New Account,
  4. Edit Account,
  5. Delete Account,
  6. Delete Customer,
  7. Mini Statement,
  8. Customized Statement.
- Integration is only tested in versions v2 & v3.
## 4. System Testing
Testing the system as a whole and verifying the modules in real scenarios.

This is done for all modules and for both the Manager and Customer roles.
In addition to that, verification of Webservice Software Interfaces for (Mini Statement, Balance Enquiry) modules is done as part of System Verification.
System testing is only performed in versions v3 & v4.
## Conclusion
Guru99's banking testing project provided a concise but profound introduction to web testing principles. It expanded my awareness of test procedures and their real-world applications, paving the way for further research in this dynamic sector. I'm keen to broaden my knowledge and apply it to more complicated problems.
