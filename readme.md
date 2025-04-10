<h1>Testing Project for HapifyMe</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: **hapifyMe**

**Tools used:** _Jira, Zephyr Squad._

<h2> Application Objectives </h2>

- Creating a social platform that allows users to connect, share content, and interact.
- Growing the user base and maximizing user retention.
- Generating revenue through advertising, premium subscriptions, or other methods.
- Providing a safe and intuitive experience for users.

<h2>Functional specifications:</h2>

The below story was created in Jira and describes the functional specifications of the "authentication" module.

'''
a. Authentication and Account Management

Account creation via email, phone number, or external accounts (Google, Apple, Facebook).

'''

The other Jira stories, in a summarised manner, can be found below:
<img width="614" alt="image" src="https://github.com/user-attachments/assets/f605b74b-a841-4797-adcc-a5bf0a1b80c9" />

Here you can find the release that was created for this project:


<img width="953" alt="image" src="https://github.com/user-attachments/assets/55e33236-3be9-4358-abb6-7b81cbb0ca6b" />

<img width="941" alt="image" src="https://github.com/user-attachments/assets/9e37fbc8-1ab2-4865-987a-647a0ee45f85" />


<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.

<h4>1.1.1. Roles asigned to the project and persons allocated</h4>

**(numele persoanelor pot sa fie fictive, doar sa treceti numele vostru ca si tester)**
<ul>
  <li>Project manager: Andrei Popescu </li> 
  <li>Product owner: Mihai Stirbea</li>
  <li>Software developer: Alexandru Ionescu</li>
  <li>QA Engineer: Timofte Alexandru-Bogdan</li>
</ul>

<h4> 1.1.2 Entry criteria defined </h4>

- business requirements must created prior to moving to the test analysis phase
- entry and exit criteria must have been defined
- test plan must be completed
- roles must have been assigned
- initial product risks must have been identified and reported to the management
  
<h4> 1.1.3 Exit criteria defined </h4>
- all test cases must have been executed
- at least 90% of the test cases must have been passed
- no high severity and high priority new bugs must be found


<h4> 1.1.4 Test scope</h4>


<h5> Tests in scope: </h5>

The following modules will be validated throughout the test process:
- Account and notification modules 
- News feed and posts
- Comments
- Friends list
- Messages and communication

The following test design techniques will be used for these modules:

- equivalence partitioning and boundary value analysis (for field dimension limitations)
- decision table (for login and account modules)
- state transition testing (for friends list management)

Test types to be used:
- positive testing
- negative testing
- functional testing
- non-functional testing

  
<h5>Tests not in scope: </h5>

No other modules besides the ones specified above will be covered through testing. 

Whitebox testing and automation testing are not in scope for this round of testing.

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>

The lack of experience of the testing team was the major obstacle during the testing process, but it was overcome through support from the senior team and through trainings that would cover the missing aspects related to software testing knowledge.


<h5> Product risks: </h5>

- The bug related to deleting a user might impact the relevance of business statistics, taking into account that deletion of the user would actually trigger user multiplication.
- The short time that was provided for testing might have led to missing important defects in the application. 

<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control<h3>

<img width="561" alt="image" src="https://github.com/user-attachments/assets/0d58a1b2-2a1c-49e2-baaf-6cf7575e528f" />

<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements.

The following test conditions were found: <br>

During testing the test conditions necessary to validate the behaviour of the application were written in Zephyr Squad. 

<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications.

The test cases covered all the areas defined under tests in scope.

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

- test environment must be up and running
- test acces must be provided
- test cases must be written and added to the proper test cycle according to prioritization
- environment smoke checks should be passed in order to provide a stable working environment

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary.

Bugs have been created based on the failed tests and are summarised below.

**Managing Post and Profile Visibility:**

- Private posts appear in the public feed.
- Settings reset after a refresh.
- Profile appears in searches even when set to invisible.

**Control over Personal Data and How It’s Used:**
- Changes are saved without confirmation.

**GDPR Options for Downloading and Deleting the Account:**
- Account is not fully deleted (active sessions persist).

**Technical and Non-Functional Requirements:**
- You can submit a script in the comment field.


Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3> 1.7 Test Completion</h3>

As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: 

<img width="1077" alt="image" src="https://github.com/user-attachments/assets/02b8faf8-c23c-4bb5-96ab-11be73f26fd2" />


Test execution chart was generated.

The final report shows that a number 5 tests have failed of a total of 30.

A number of 6 total bugs were found, and they were reported together with their priority and severity. 
