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
* Filter an order 
* Manually Adding/Modifying an order 

1.3. Functionalities and tests out of scope

*	Non-functional testing like stress, performance is beyond scope of this project.
*	No QA support for mobile applications developed. Only web applications will be tested.
*	Automation testing is beyond scope.

The other functionalities from dashboard that are not mentioned for testing in this release, will not be tested. These modules are: Catalog, Extensions, Design, Sales – with the remaining functionalities (Subscriptions, Returns, Gift Vouchers), Customers, Marketing, System, Reports.

#### 2.Test Process
2.1. Test planning
Roles and responsibilities: 

| Name | Role | Will test |
| :---         |     :---:      |    :---:    |
| Man Bianca   | Tester     | View an order    |
|     |       | Filter an order      |
|     |       | Manually Adding/Modifying an order      |

Entry criteria:
*	Verify if functional business specifications are defined.
* The partial or complete testable code is available.
*	Verify if roles needed for the project are allocated.
*	Verify if test strategy is developed.

Exit criteria:
*	All test cases have been executed
*	90% of tests are passed
*	No Critical issues/bugs have Open status (All unresolved bugs have low priority and low severity)
*	Exploratory testing performed on the features: View an order, Filter an order, Manually Adding/Modifying an order
*	Update tests are 100% passed (update tests will not generate other new issues that impact the application)
*	The schedule has been achieved

Risks:

Project risks:
* Incomplete or Changing Requirements: Unclear, incomplete, or changing requirements can lead to misunderstandings, scope creep, and difficulty in defining test cases accurately.
* Schedule Delays: Tight deadlines, unexpected delays in development, or inadequate time allocated for testing can result in rushed testing efforts, compromised quality, and increased project risks.
* Resource Constraints: Insufficient staffing, inadequate testing tools, or limited access to testing environments can hamper the testing process and compromise the effectiveness of testing activities.
* Scope Creep: Expansion of project scope beyond the initially defined boundaries can result in additional testing efforts, increased complexity, and challenges in maintaining test coverage.
* Technical Challenges: Complex system architecture, integration issues, compatibility issues across platforms and devices, or limitations of testing tools can pose technical challenges and hinder the effectiveness of testing efforts.
* Communication Breakdowns: Poor communication among project stakeholders, misalignment of expectations, or lack of collaboration between development and testing teams can lead to misunderstandings, delays in issue resolution, and inefficiencies in testing activities.
* Data Risks: Inadequate or inappropriate test data, data privacy concerns, or data integrity issues can compromise the effectiveness of testing and lead to inaccurate test results.
* Environmental Risks: Unstable or inadequate testing environments, infrastructure failures, or configuration issues can disrupt testing activities and impede the identification of defects.
* Quality Risks: Insufficient test coverage, inadequate test cases, or ineffective defect management processes can result in undetected defects, leading to compromised quality and increased rework efforts.


Product risks:
* Integration Challenges: Integration with third-party systems, services, or APIs can introduce risks related to compatibility, data exchange, and interoperability, requiring thorough integration testing to validate seamless interaction.
* Performance and Scalability: Performance-related risks, such as slow response times, resource utilization issues, or scalability limitations, can impact user experience, system reliability, and the ability of the software to handle increasing loads over time.
* Security Vulnerabilities: Security risks, including vulnerabilities, weaknesses, or exposure to malicious attacks, can compromise the confidentiality, integrity, and availability of data, necessitating robust security testing to identify and address potential threats.
* Usability and Accessibility: Usability issues, navigation challenges, or accessibility barriers for users with disabilities can affect user satisfaction, adoption rates, and compliance with regulatory requirements, highlighting the importance of usability and accessibility testing.
* Platform and Device Compatibility: Compatibility risks associated with different operating systems, web browsers, devices, or screen resolutions can lead to inconsistencies in functionality, layout, or performance across platforms, requiring comprehensive compatibility testing.
* Data Integrity and Accuracy: Risks related to data integrity, accuracy, or consistency can arise from errors in data processing, storage, or manipulation, necessitating data validation and verification through thorough testing of data inputs, outputs, and calculations.
* Fault Tolerance and Disaster Recovery: Risks associated with system failures, downtime, or data loss due to hardware failures, software bugs, or natural disasters can impact business continuity and operational resilience, requiring testing of fault tolerance mechanisms and disaster recovery procedures.
* Localization and Internationalization: Risks related to localization (adapting the software for specific languages, cultures, or regions) and internationalization (designing the software to support global markets) can affect usability, functionality, and acceptance in diverse markets, necessitating localization and internationalization testing.

2.2. Test analysis
* The next functionalities will be tested: View an order, Filter an order, Manually Adding/Modifying an order.
* I will analyze the business requirement specifications to ensure that there are no mistakes. 
* The testing process will be executed, based on the requirements sent by the client.
* The following test conditions were found: 
![Test conditions opencart](https://github.com/ManBianca/Project-OpenCart/assets/159307072/2709b653-fa85-4b5d-bdac-adfa484aab1b)


2.3. Test design
* Functional test cases were created in Zephyr Squad and can be accessed: [here](https://github.com/ManBianca/Project-OpenCart/blob/main/Jira%20Test%20Cases.pdf).
* The test design techniques used for generating test cases are:  functional testing, positive testing and negative testing, equivalence partitioning, boundary value analysis.

2.4. Test implementation
* Testing environment is up and running: https://demo.opencart.com/
* Access to the test environment is given: username demo, pass: demo
* Cycle summary was created.
* Test cases were added to the cycle summary: [Cycle Summary](https://github.com/ManBianca/Project-OpenCart/blob/main/Cycle%20Summary%20-%20Sales%20module%20cycle.jpg).

2.5. Test execution
* Test cases are executed on the created test Cycle summary: [Cycle Summary Execution](https://github.com/ManBianca/Project-OpenCart/blob/main/ZFJ-Executions-02-12-2024.csv).
* Bugs have been created based on the failed tests. The complete bug reports can be found here: [Bug Reports](https://github.com/ManBianca/Project-OpenCart/blob/main/PDF%20(Jira).pdf).
* Full regression tests pack was executed.

2.6. Test completion
* As the exit criteria were met and satisfied as mentioned in the 2.1 section, this feature is suggested to go live by the QA team.
* The traceability matrix was generated:
  ![Traceability Matrix modificata](https://github.com/ManBianca/Project-OpenCart/assets/159307072/28ab837f-17ec-4671-94ca-a6e35d4430d8)
  ![Traceability Matrix modificata 1](https://github.com/ManBianca/Project-OpenCart/assets/159307072/ea09b9f8-4168-4aab-96b8-e9fafc19c0b2)


* Test execution chart was generated:
  
![Test Execution chart](https://github.com/ManBianca/Project-OpenCart/assets/159307072/03cbedf6-369c-4aa2-aaf6-3449985166d0)


2.7. Test monitoring and control

Periodic reports are generated to check the project status: status for the test cases executed, status for the converge of the business requirements, etc

#### 3.Conclusions

After Testing the functionalities for View an Order, Filter an Order, Manually Adding/Modifying an Order, I have reached the following conclusions:
* View an Order: The functionalities tested for the correct visualization of the Sales module have been well implemented, so that an admin can have all the details about the site's orders at his fingertips in a table. The checkbox, sorting, navigating among the orders is easy and no aspects were found that require changes.
* Filter an Order: The methods of filtering orders by 'Order ID', 'Customer', 'Order Status', 'Total $' depend on 'Added Date' and 'Modified Date', but in these tests performed in some positive conditions, there were no noticed problems to solve.
* Manually Adding/Modifying an Order:
  
The BAMM-31 story was based on testing the addition of new commands and everything involving the add order button. Even if the functionality of the button itself was well implemented, major problems were found with command values exceeding 100.000.000.000$, a bug was reported and requires attention to be fixed.

The tests carried out within the BAMM-32 story followed functionalities such as modifying commands and deleting them. The tested functionalities are well implemented and easy to use, but two minor problems related to the deletion of orders were also found, bugs were reported. The two defects found do not affect the proper functioning of the functionalities.

In total there are 4 stories covered by 17 tests, each of those tests were written and executed as shown above in 2.5. section.

In 2 of the 4 stories, 3 bugs were discovered that were reported and fixed. These have minor severity, with medium priority. These are defects that do not lead to failure and can be solved during the development activities.

In general, the tests had a satisfactory finality and a perfect functionality. It is recommended to make adjustments on the minor aspects discovered to provide a better quality and experience for the admin and not only.

