# Project-OpenCart
## My Project in Manual Testing IT Factory
### Test Plan
#### 1.Introduction

1.1 The objective of this project is to raise the trust in the quality as high as possible before releasing it to customers. We have to apply all the possible techniques, try to find all the bugs we can, to ensure that the functionalities are correctly implemented and they respect the business requirements. 

The Test Plan is designed to describe all details of testing for the Sales module from OpenCart platform.

Application under test: https://demo.opencart.com/admin/

Documentation: http://docs.opencart.com/en-gb/introduction/

API Documentation: https://docs.opencart.com/en-gb/system/users/api/

Tools used: JIRA, Zephyr Squad.

1.2 Functionalities in scope

In this release, I will focus and test the Sales module, with the following functionalities:
* View an order from the Order list
* Searching for an order 
* Manually Adding/Modifying an order 

1.3. Functionalities and tests out of scope

*	Non-functional testing like stress, performance is beyond scope of this project.
*	No QA support for mobile applications developed. Only web applications will be tested.
*	Automation testing is beyond scope.

The other functionalities from dashboard that are not mentioned for testing in this release, will not be tested. These modules are: Catalog, Extensions, Design, Sales – with the remaining functionalities (Subscriptions, Returns, Gift Vouchers), Customers, Marketing, System, Reports.

#### 2.Test Process
2.1. Test planning
Roles and responsibilities: Man Bianca - role - tester.

Entry criteria:
*	Verify if the Test environment is available and ready for use.
*	Verify if test tools installed in the environment are ready for use.
*	Verify if Test Data is available and validated for correctness of Data.
*	Verify if functional business specifications are defined.
*	Verify if roles needed for the project are allocated.

Exit criteria:
*	all test cases have been executed
*	90% of tests are passed
*	no Critical issues/bugs have Open status (All unresolved bugs have low priority and low severity)
*	exploratory testing performed on the features: View an order, Searching for an order, Manually Adding/Modifying an order
•	update tests are 100% passed (update tests will not generate other new issues that impact the application)
*	the schedule has been achieved

Risks:
*	stability risks like the system slows down, the system encounters functionality problems, crashes, disconnects, etc, can affect the performance of the web application
*	IE browser might have performance issues
*	the web page pagination could be impacted when opened on mobile devices
*	stress conditions like high user loads, heavy data processing, network congestion,  might impact the web application
*	new browser might not be supported
*	Improper communication among team members or with enterprise stakeholders can lead to a low quality of the product

2.2. Test analysis
* The next functionalities will be tested: View an order, Searching an order, Manually Adding/Modifying an order.
* I will analyze the business requirement specifications to ensure that there are no mistakes, 
* The testing process will be executed, based on the requirements sent by the client
* The following test conditions were found: [Test conditions](https://github.com/ManBianca/Project-OpenCart/blob/main/Test%20conditions%20opencart.jpg) .

2.3. Test design
* Functional test cases were created in Zephyr Squad and can be accessed here: [Test cases](https://github.com/ManBianca/Project-OpenCart/blob/main/PDF%20(Jira).pdf).
* The test design techniques used for generating test cases are: equivalence partitioning, boundary value analysis.

2.4. Test implementation
* Testing environment is up and running: https://demo.opencart.com/
* Access to the test environment is given: username demo, pass: demo
* Cycle summary was created.
* Test cases were added to the cycle summary: [Cycle Summary](https://github.com/ManBianca/Project-OpenCart/blob/main/ZFJ-Executions-02-12-2024.csv).

2.5. Test execution
* Test cases are executed on the created test Cycle summary: cycle summary execution.
* Bugs have been created based on the failed tests. The complete bug reports can be found here: [bug reports](https://github.com/ManBianca/Project-OpenCart/blob/main/PDF%20(Jira).pdf).
* Full regression tests pack was executed.

2.6. Test completion
* As the exit criteria were met and satisfied as mentioned in the 2.1 section, this feature is suggested to go live by the QA team.
* The traceability matrix was generated and can be found here: [Traceability Matrix](https://github.com/ManBianca/Project-OpenCart/blob/main/Traceability%20Matrix.jpg).
* Test execution chart was generated: [test execution chart](https://github.com/ManBianca/Project-OpenCart/blob/main/Test%20Execution%20chart.jpg).

2.7. Test monitoring and control

Periodic reports are generated to check the project status: status for the test cases executed, status for the converge of the business requirements, etc
* Two weeks report 1
* Two weeks report 2
