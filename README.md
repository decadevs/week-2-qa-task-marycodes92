ANSWERS
1.	Test coverage is a standard for measuring or evaluating the extent to which lines of code were executed during a particular test suite for a program. Test coverage measures how thorough your testing is while running a test suite.
Test coverage is important software testing because it helps to ascertain exactly how much of code is actually tested, it provides insight and focus to help developers improve their tests even before they start building a program. It helps keep testing up to the required standard. Without test coverage, it is difficult for us to determine the degree in which our test cases has gone in making sure a quality product is released.

2.	Testing types are the kinds of tests that can be performed on a software/program while testing techniques are the rules to apply while writing test cases in order to have a better test coverage. These are rules a QA personnel should follow when performing any of the testing types. 

3.	There are two types of testing which are functional and non-functional testing. 
Functional testing is a kind of testing that focuses on testing the functionality of a software. That is, checking what the software can actually do and how it works. In this kind of testing the QA engineer validates the software against the functional requirement/specifications of the software. We have various types of Functional test that can be performed on a software and they are;
(a)	Unit Testing: this is a type of functional testing where individual unit or component of a software application are tested unit by unit. The main aim of this test is to validate that each unit of the software is actually performing the task it was meant to perform. This test is usually performed by the software developers, in some cases it is performed by independent software testers. Before performing the unit testing, there are things you should put in place like; (i) unit test plan that is; a detailed document that describes the test strategy, objectives, schedule, estimation, deliverables and resources required to perform the testing. (ii) Unit Test Cases which involves the characteristics that are critical to the success of the unit. (iii) Unit test, here the unit test is done proper. Unit testing is beneficial cause it’s reliable; it increases confidence in changing and maintaining code, it is cost effective because each time a unit of code is changed, you will be able to detect any error introduced as a result of the change early enough and fix it, it’s easy to maintain code, debugging is easy, etc. 
(b)	Integration Testing: in this type of functional testing, individual units of code are combined and tested as a group. The main aim of this testing is to detect faults in the interaction between integrated units. Things to prepare before performing this test are; integration test plan, integration test scripts, and then perform the integration test. There are several approaches to integration testing; (i) Big Bang: this is an approach where all or most of the units are combined and tested at once. This approach can only be used if the testing team receives the entire software at the same time. (ii) Top-Down: this is an approach where top level unit are tested first and lower-level unit are tested step by step after. This approach is used when top-down development approach is followed (iii) Bottom-up: this approach is where bottom level unit are tested first and top-level unit are tested step by step after. This approach is used when bottom-up development approach is followed. (iv) Hybrid: this approach involves both the top-down and bottom-up approach.
(c)	System Testing: this kind of functional testing is a testing where a complete and integrated software application is tested. This kind of test is performed after the integration testing and before the acceptance testing. Things to prepare before performing this test are; system test plan, system test cases, and then perform the system test. There some analogies in system testing which are; during the development of a software, all its components are manufactured separately, each unit tested separately, when two or more software, all its components are manufactured and each unit tested separately, when two or more unit is ready, they are integrated in the integration testing phase and after integration, the system testing is performed. 
(d)	Interface Testing: this is a level of testing performed to check if two systems communicate accurately between each other. Interface testing is divided into three phases; (i) Configuration and development: once the system is configured and development starts, the configuration needs to be tested as per the requirement. (ii) Validation: when the development is completed, the interface needs to be validated and verified. (iii) Maintenance: when the whole software is completed, deployed and working, the interface needs to be monitored for its performance and any new issues due to the changes made or deteriorating performance. We perform Interface testing because it is required to check if the server execution is working well, to make sure that error handling is done properly and appropriate error messages are shown for queries made by the application, it is required to check when the connection to the server is reset, and to check the impact of network failure on the communication between the components.
(e)	Regression Testing: this kind of functional testing is where the testing team identify the stability of the software with the changing requirements. There are various techniques in regression testing which are as follows; (i) Retest All: the whole test cases in regression test are re-executed to make sure that there are no errors introduced as a result of change in the code. (ii) Regression Test Selection: in this method, test cases to be re-executed are selected from the test suite. (iii) Test case prioritization: Here test cases with high priority are executed first then the once with medium priority and then those with low priority. (iv) Hybrid: this is a combination of regression test selection and test case prioritization.
(f)	Acceptance Testing: this is a level of functional testing where a software application is tested for acceptability. The purpose of this test is to evaluate whether the software complies with the business requirement and whether it is acceptable for delivery. This test is performed by the customer support team, management team or customers. Acceptance testing has different types; (i) User Acceptance: testing whether the software works for the user correctly for the specified purpose. (ii) Business Acceptance: here, you test whether the software meets the business goals or not. (iii) Contract Acceptance: this is a contract which states that once the software goes live it should be tested after a pre-determined period of time and it must pass all the test cases provided in test suite, Etc.

Non-functional Testing: This is a type of testing done on a software to check the non-functional requirement such as the way the software operates, performance, usability, reliability, etc. We have sub-testing types under non-functional testing which are;
(a)	Documentation Testing: this helps takes record of testing effort required. This includes test plan, test cases and requirement section.
(b)	Installation Testing: this kind of testing involves what the users need to do in order to install and setup the new software successfully. In the cause of performing this test, you also check whether the user is able to uninstall the application and remove all the folders associated with the application without any problem.
(c)	Performance Testing: This is a type of non-functional testing carried out to ascertain the systems performance in terms of responsiveness and stability under various workload. We have four types of performance testing (i) load: this is carried out to check the behaviour of a system under a specific load. (ii) Stress: this is done to ascertain the behaviour of a system beyond the limits of its expected workload. (iii) Endurance testing: this is done to check the behaviour of a system when a particular workload is given continuously. (iv) Spike: is done by suddenly increasing the workload by a very large amount and measuring the performance of the system.
(d)	Reliability Testing: This is a kind of testing done to ensure that the software is fault free and its reliable for the purpose it was intended. Reliability testing has the following types; (i) Feature: here you make sure that each function in the software is executed at least once and ensure that interaction between unit are minimized. (ii) Regression: this is performed whenever new functionality is been added or removed so as to be sure no errors or bugs are added as a result of the change. (iii) Load: this is done to test whether the software supports the required load by getting the breaking point. In order to get the break point of a software, the load is increased continuously until the software begins to hang.   
(e)	Security Testing: this is carried out to discover the vulnerabilities of the software and make sure that the data and resources of the system are protected from possible threats. Areas to consider while performing security test; network security, system security, client security, sever security, etc. Rules for performing security testing; (i) Access the Application: this is often done implicitly while covering the functionality. This means that whether it is a desktop or mobile application, access security is implemented by rules and rights management. (ii) Data Protection: here you make sure that users can only be able to access and make use of only the data that is relevant to them, etc. (iii) Brute Force Attack: this is mostly done by some software tools. The concept is, by using a valid user ID, the software attempts to get the associated password by trying to login again and again. (iv) SQL injection: for any input field of the website, field-length should be defined small enough to restrict input of any script. Etc.  

4.	https://drive.google.com/drive/folders/13DDw9QwGWU2nE7D651YmxTdh-c5Lq49s?usp=sharing

5.	Testing techniques are rules used while writing test cases in order to have a better test case coverage.
Types of testing techniques and examples;
(a)	Error Guessing 
(b)	Equivalence partitioning 
(c)	Boundary value analysis 
(d)	Decision table technique
(e)	State Transition technique 

ERROR GUESSING: this type of testing technique does not follow any specific rule, it depends on the individual analytical thinking, experience from previous testing jobs. Here, the tester makes guess of errors or error prone areas and then writes test cases to expose the errors. To be able to develop test cases here, the tester can use past experience to identify the conditions for the test. In order to achieve a good test coverage using error guessing, the tester has to be skilled and experienced. Most importantly, while guessing with experience, the tester should have an understanding of the software currently under test in order not to deviate from the software’s specification requirement.

Examples:
(a)	Given a bank App and I am required to test the functionality. 

Using Error Guessing below are some of the Test scenarios I will guess
•	Check if a user can actually login in successfully 
•	What happens if a user is not registered in the application.
•	What happens if the user enters a wrong password 
•	What if the user forgets his/her password?
•	Check if the user can perform transactions in the app like purchase airtime, pay bills, etc as per the requirement.
•	What happens when a user wants to pay bill or purchase airtime or transfer money but his/her available balance is 0. 


(b)	Given an NYSC registration App and I am supposed to test the functionality of uploading a passport photograph with conditions   

Using Error Guessing below are some of the Test scenarios I will guess
•	Uploading a passport that exceeds the maximum size limit
•	Uploading a passport that does not have the required file format
•	Uploading a passport that does not have the required resolution 


EQUIVALENCE PARTITIONING: This is a testing technique that breaks the input data of a software into various classes (valid and invalid) from which test cases can be derived. Here test cases are designed to cover each class at least once.

Examples:
(i)	Given a ATM machine that has a minimum withdrawal limit of N1,000 and maximum withdrawal limit of N20,000

Here, I will divide my test cases into classes of Valid and Invalid. 

Classes	Test Cases	Expect Result
Valid Cases 	(i)	N1000
(ii)	N9000	PASS 
Invalid Cases	(i)	N500
(ii)	N25,000	FAIL 

(ii) 	Given a school system that admits students to a school. For a student to be admitted he/she must at least 50% and at most 99% in the entrance examination.

Classes	Test Cases	Expect Result
Valid Cases 	(i)	50%(ii)	76%	PASS 
Invalid Cases	(i)	38%
(ii)	108%	FAIL 


BOUNDARY VALUE ANALYSIS TECHNIQUE: This testing technique is based at the boundaries of input domain. 

Examples:
(i)	Given a POS machine that has a minimum transfer limit of N1,000 and maximum transfer limit of N100,000

Here, I will divide my test cases into different range. 

Range 	Test Cases	Expect Result
N 1,000 – 1 	N 999	Fail
N 1,000	N1,000	Pass 
N 1,000 + 1	1001	Pass
100,000 – 1	99,999	Pass
100,000	100,000	Pass
100,000 + 1	101,000	Fail 

(ii)	Given a school system that admits students to a school. For a student to be admitted he/she must at least 50% and at most 100% in the entrance examination.

Range	Test Cases	Expected Result
50% – 1	49%	Fail
50%	50%	Pass
50% + 1	51%	Pass
100% - 1	99%	Pass
100%	100%	Pass
100% + 1	102%	Fail 
DECISION TABLE TECHNIQUE: This is a testing technique where you test with multiple input. In this technique, there is a visual combination of input and outputs where inputs are conditions or cases and inputs are actions to be performed. 
Examples:
(a)	Golden morn company is running a promo where they give 5% discount to new customers and 3% discount to old customers. They have an Application for that determines the status of the customer and removes the discount associated to the customer. 

	Rule 1	Rule 2	Rule 3	Rule 4
New Customer (5%) 	T	T	F	F
Old Customer (3%)	T	F	T	F
Result	Failed	Passed 	Passed 	Failed 


(b)	Given a recruitment application that helps a company to recruit staff. There are conditions a candidate must meet in order to be qualified for recruitment; the candidate must be 30years of age, the candidate must be a female and the candidate must be a Nigerian. 

	Rule 1	Rule 2	Rule 3	Rule 4	Rule 5	Rule 6	Rule 7
30 years 	T	T	T	T	F	F	F
Female	T	T	F	F	T	T	F
Nigerian  	T	F	T	F	T	F	T
Result	Passed	Failed	Failed	Failed	Failed	Failed	Failed


 
STATE TRANSITION TECHNIQUE: This type of testing technique is used to check the changes in the state of the application under different inputs. State transition should be used when a tester is testing the application for a limited set of input values or when the tester wants to test sequence of events which happen in the application under test.

Examples: 
(i)	The Human Resource Manager of Nasco company wants to recruit for the position of a marketing manager who he wants to be an indigene of Anambra because they want to market their product in Anambra. Applications are submitted to the HR team who checks applicants qualification and then forwards to the HR Manager who then checks if the applicant is an Indigene of Anambra.















 
(ii)	Given an application that enables a registered user to login (with correct registered details) and order for items from a mall but blocks the user after entering incorrect details three times. 





















 

6.	Title: Login form – Authenticate Successfully 
Description: A registered user should be able to successfully login to the form.
Precondition: the user must already be registered with an email address and password.
Assumption: a supported browser is being used.

Test Steps:
1.	Navigate to the form
2.	In the ’email’ field, enter the email address of the registered user.
3.	Enter password of the registered user
4.	Click ‘Sign In’
Expected Result: A page displaying a form should load, showing information that a form should contain.
TEST SCENARIOS
Scenario 1: Check Email field functionality
Pre-conditions: 
1.	Email must be a valid email format.
2.	Email characters cannot be less that 15 characters but not greater than 200 characters

Testing Technique Used
Equivalence Partitioning: I break my test into valid and invalid class
Implementation of Equivalence Testing 
Classes	Test Cases	Expect Result	
Valid Cases 	(iii)	onuorahmary@gmail.com
(iv)	50 characters	Pass 	Pass 
Invalid Cases	(iii)	Maryonuorah
(iv)	12 characters
(v)	203 characters 	Fail 	Fail 

Boundary Value Analysis: I break my test into different range
Range 	Test Cases	Expect Result
15 – 1 	14 characters 	Fail
15 	15 characters 	Pass 
15 + 1	16 characters 	Pass 
200 – 1	199 characters 	Pass
200	200 characters 	Pass
200 + 1	207 characters 	Fail 

Scenario 2: Check password field functionality
Pre-conditions: 
1.	Password should contain at least 8 characters and at most 20 characters
2.	Password must contain at least one character, one number and one capital letter

Testing Technique Used:
Equivalence Partitioning: I break my test into valid and invalid class
Implementation of Equivalence Testing 
Classes	Test Cases	Expect Result	Actual Result
Valid Cases 	(i)	11 characters
(ii)	Mary#onuo2	Pass 	Pass
Invalid Cases	(i)	0 characters (submitting empty fields)
(ii)	3 characters
(iii)	23 
(iv)	Mary8onuorah	Fail 	Fail 

Boundary Value Analysis: I break my test into range
Range 	Test Cases	Expect Result	Actual Result
8 – 1 	7 characters 	Fail	Fail
8	8 characters 	Pass 	Pass 
8 + 1	9 characters 	Pass 	Pass 
20 – 1	19 characters 	Pass	Pass
20	20 characters 	Pass	Pass
20 + 1	21 characters 	Fail 	Fail 

Decision Table Technique 
The rules are in the row and the conditions in the column.
	Rule 1	Rule 2	Rule 3	Rule 4	Rule 5	Rule 6	Rule 7	Rule 8
Character 	T	T	T	T	F	F	F	F
Number 	T	T	F	F	T	T	F	F
Capital letter 	T	F	T	F	T	F	T	F
Result	Passed	Failed	Failed	Failed	Failed	Failed	Failed	Failed 

Scenario 3: Check Login Button functionality
Pre-conditions: 
The Login button should be enabled if the user has entered all the valid required fields (email & password)

The Testing Technique Used here is Decision Table Technique 
Implementation of Decision Table Technique 
The rules are in the row and the conditions in the column.
	Rule 1	Rule 2	Rule 3	Rule 4
Email  	T	T	F	F
Password 	T	F	T	F
Enable Button	Passed	Failed	Failed	Failed 

 
7.	Using a Decision Table Technique 
Requirements:
•	you can upload only .jpeg format, 
•	file size must be less than 32kb, 
•	Resolution must be only 137*177


	                Rule 1	Rule 2	Rule 3	Rule 4	Rule 5	Rule 6	Rule 7	Rule 8
.jpeg format 	    T	    T	    T	    T	    F	    F	    F	    F
less than 32kb	    T	    T	F	F	T	T	F	F
Resolution 137*177 	T	F	T	F	T	F	T	F
Result	Passed	Failed	Failed	Failed	Failed	Failed	Failed	Failed 



8.	









 
9.	




















10.	Error Guessing Technique 

I will make guesses as below and with the guess I will develop test cases
	Does it reply to messages
	Does it auto-forward and redirect messages
	Is it able to send copies of a message to many people
	Can it automatically fill and retrieve messages
	Does it notify a user if a message cannot be delivered
	Does it automatically puts date and time to emails
	Can signatures be attached to mail
	Can files, images, videos be sent as attachments in the required formats
	Check if webmail and mobile email can be used to receive and send messages 



