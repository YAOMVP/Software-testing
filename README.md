# SoftwareTesting NoteBook

*Learned with The Complete 2023 Software Testing Bootcamp, Tarek Roshdy,Nezam Academy.*

# :one:software Development Lifecycle(SDLC)

![1678929557588](README.assets/1678929557588.png)



There are 2 ways of software development lifecycles

1. Sequential development ~顺序开发~
2. Interactive & Incremental ~迭代和增量模型。~





##1.Sequential development

![1678929982473](README.assets/1678929982473.png)

1. at the beginning.The customer has an idea. So he begins searching for a company that develops this idea for him. So at the beginning the customer has some requirements.
2. He tells us his requirements and we begin writing them in a sequence of steps and in a good format. 
3. Then the developers and the designers sit together and begin designing the software. How will we deliver the requirements to this customer. Then we begin writing our code. We begin building the project. 
4. After writing the code and integrating it. here comes the testing part. We begin the testing and while we test the software we find defects. 
5. These defects are fixed and then we release our product to the customer hoping that he likes it.



###Waterfall Model 

Testing begins at the end of the process.

![1678930798850](README.assets/1678930798850.png)





### V-Model 

Testing starts early from the requirements gathering step.

![1678930838775](README.assets/1678930838775.png)





## 2.Interactive & Incremental

#### Incremental Model

We develop software in increments.We finish a part of the software, we gather its requirements. We design it, we develop it, and we test it.

Then we move to the next section and perform the whole lifecycle on this section and so on.

#### Interactive Model

For example we draw our painting with only pencils. Then we add a layer of colors then at the final iteration we add all the colors and finish our painting.

A very important note that we may have a model which is iterative and incremental at the same time. 





# What is software Testing

![1678931859244](README.assets/1678931859244.png)

![1678931895905](README.assets/1678931895905.png)



## Testing is dynamic and static

### Dynamic testing

Execute the software. I will execute my code if I will execute my system, if I will open the website and do things inside it or the Android applications.

### Static testing

We do not execute the software.We may review our code search for maintainability~n.可维护性~ issues in it, make sure that it follows the standards.We may review the requirements we review the design we review the user manuals, any type of review.



## Testing performs validation & verification

### Validation

Build the right product. 

We build the right product. The product that the user wants, when they use or comes to us.He will be happy with this product.

### Verification

Build the product right.

We built the product in the right way. So the architecture, the design, the performance, the security. Software testing performs both of them.



# Objectives of Testing~软件测试的目标~

![1678933221215](README.assets/1678933221215.png)

We need to evaluate the work products. The work products are anything that is produced, whether it is the requirements, the code, the test cases, test plan, the design, the summary reports all of these are considered as work products.

So we evaluate the work products. we ensure requirements fulfillment we ensure that our software fulfills,the requirements of the client.

We build confidence inside our components. We need to make sure that our components and systems are good enough.

Of course we try to find defects and we try to prevent defects by early testing.

If we begin testing early especially static testing that will prevent defects from occurring late in the lifecycle.

We provide information to stakeholders. The stakeholders like the team leader, the manager, the client, and the user. We provide information to stakeholders. We give them enough information about the level of the quality so that they can decide is this software ready to be delivered or not.

We reduce the risk of failures in user operation. We try to comply with laws and regulations.

If we have a contract with the user we try to make sure that our product satisfies this contract. And these objectives may vary depending on the type and the level of testing that we are performing now.



##Testing & Debugging

We begin testing it and reporting the defects to the developer.We are not the one who remove the defects.

The removal of defects which is called debugging is a development activity.

After the developer removes the defects by debugging we begin

confirmation or retesting. We test the software again in order to make sure that the defects that we already reported is really fixed.



#Test Process Activities

## Software Test != Test Execution

It is a process, which includes many different activities.





![1678934100334](README.assets/1678934100334.png)

- We begin by test planning, monitoring and control, analysis, design, implementation, execution and completion. So at the beginning we write our test plan.


- Then while we are moving in our project we begin to monitor our progress. We begin to compare our actual progress to the expected progress that is written inside the plan. If they are the same we continue in our project. If there is a difference between them, we perform control activities so control activities or any corrective actions that we should use in order to follow our plan. Then we analyze our requirements, with read the requirements. We search for defects inside it and we analyze it in order to find the test conditions or the test scenarios. Then after designing our test cases we begin the implementation. We organize our test cases into test suites. We design our test environment and the environment is the place that we will begin our testing on.

- We execute the tests, find defects, report them, perform retesting and regression

  testing. Then we finish our work. write test progress reports and test summary reports.

  

  

  

  ## 1. Sequential development
  1. at the beginning. The customer has an idea. So he begins searching for a company that develops this idea for him. So at the beginning, the customer has some requirements.
  2. He tells us his requirements and we begin writing them in a sequence of steps and in a good format. 
  3. Then the developers and the designers sit together and begin designing the software. Then we begin writing our code. We begin building the project. 
  4. After writing the code and integrating it. here comes the testing part. We begin the testing and while we test the software we find defects. 
  5. These defects are fixed and then we release our product to the customer hoping that he likes it.

  ### Waterfall Model 
  Testing begins at the end of the process.

  ### V-Model 
  Testing starts early from the requirements gathering step.
  ## 2.Interactive & Incremental

  #### Incremental Model
  We develop software in increments. We finish a part of the software, and we gather its requirements. We design it, we develop it, and we test it.Then we move to the next section and perform the whole lifecycle on this section and so on.

  #### Interactive Model
  For example, we draw our painting with only pencils. Then we add a layer of colors then at the final iteration we add all the colors and finish our painting.
  A very important note is that we may have a model which is iterative and incremental at the same time. 

  # What is Software Testing

  ## Testing is dynamic and static

  ### Dynamic testing
  Execute the software. I will execute my code if I will execute my system if I will open the website and do things inside it or the Android applications.

  ### Static testing
  We do not execute the software. We may review our code search for maintainability~n.可维护性~ issues in it, make sure that it follows the standards. We may review the requirements we review the design we review the user manuals, any type of review.

  ## Testing performs validation & verification

  ### Validation
  Build the right product. 
  We build the right product. The product that the user wants, when they use or comes to us.He will be happy with this product.

  ### Verification
  Build the product right.
  We built the product in the right way. So the architecture, the design, the performance, the security. Software testing performs both of them.

  # Objectives of Testing
  We need to evaluate the work products. The work products are anything that is produced, whether it is the requirements, the code, the test cases, the test plan, the design, or the summary reports all of these are considered work products.
  So we evaluate the work products. we ensure requirements fulfillment we ensure that our software fulfills, the requirements of the client.
  We build confidence inside our components. We need to make sure that our components and systems are good enough.
  Of course, we try to find defects and we try to prevent defects through early testing.
  If we begin testing early especially static testing that will prevent defects from occurring late in the lifecycle.
  We provide information to stakeholders. The stakeholders like the team leader, the manager, the client, and the user. We provide information to stakeholders. We give them enough information about the level of quality so that they can decide if this software is ready to be delivered or not.
  We reduce the risk of failures in user operation. We try to comply with laws and regulations.
  If we have a contract with the user we try to make sure that our product satisfies this contract. And these objectives may vary depending on the type and the level of testing that we are performing now.

  ## Testing & Debugging
  We begin testing it and reporting the defects to the developer. We are not the ones who remove the defects. The removal of defects which is called debugging is a development activity.
  After the developer removes the defects by debugging we begin confirmation or retesting. We test the software again in order to make sure that the defects that we already reported are really fixed.

  # Test Process Activities

  ## Software Test != Test Execution

  It is a process, which includes many different activities.
  - We begin with test planning, monitoring, and control, analysis, design, implementation, execution and completion. So at the beginning, we write our test plan.

  - Then while we are moving in our project we begin to monitor our progress. We begin to compare our actual progress to the expected progress that is written inside the plan. If they are the same we continue with our project. If there is a difference between them, we perform control activities so control activities or any corrective actions that we should use in order to follow our plan. Then we analyze our requirements, by reading the requirements. We search for defects inside it and we analyze it in order to find the test conditions or the test scenarios. Then after designing our test cases we begin the implementation. We organize our test cases into test suites. We design our test environment and the environment is the place where we will begin our testing.

  - We execute the tests, find defects, report them, and perform retesting and regression testing. Then we finish our work. write test progress reports and test summary reports.

    

----------------------------



# System Integration testing

let's have WhatsApp for example. We have a system which is the android application, we have another system which is the iOS app, and a third system which is the desktop application.

Each one of them is a separate system that needs to be tested. In system integration testing, we test the interaction between the three systems, so for example if I login from my mobile and send a photo to a friend, the photo should appear at the same time on the desktop application and so on.

##system integration testing vs system testing

For example, if you are testing Uber mobile application.

System integration testing is testing the integration between the rider app and the driver app.

System testing is testing the application (Rider app for example) as a whole for its compliance with functional and non-functional requirements.



# Testing type

## 1.Functional Testing

==Test the main functions of the software.==

Facebook. We have log in functionality. We have registration. So I should log in so I will test the login functionality.



##2.Non-Functional Testing

==How does the system perform.==

For example we have the login functionality, it is working from a functional way but is it fast enough? Is the response time of this functionality good? Is the user interface appealing enough? Can not answer it with yes/no.



## 3.Black-Box Testing

==We test without looking at the internal structure of the software.==

If I have a mobile app I will provide input and wait for the output. The application is like a black box. I will not open it and look at the code. I would not look at the database. I will not look at or review the APIs.



## 4.White-Box Testing

==Provide input to the software also look at the internal structure of the software.==

What is happening in the code, in the database, in the APIs, while I'm performing this input, while I'm providing this input to go to the output. This is a more advanced topic of testing.



## 5.Dynamic Testing

==We are executing the software in the test process.==

if we run the code, this is dynamic testing.

If we run the application this is dynamic testing.

For example on the login page, dynamic testing means that I must provide email, password, and provide input to the software.



##6.Static Testing

==We don't execute anything in the software.==

Like reviewing the requirements, reviewing the user stories.If we review the code that the developer wrote. If we review a prototype of the application UI and give some notes about it. All of this is considered as static testing.



##7.Retesting(Confirmation Testing)

==Test the changed area.==

We wrote a bug report, we sent it to the developer, we should perform retesting or confirmation testing, we say this defect is solved or this defect is not solved.



##8.Regression Testing

==Test parts of the software that did not change.==

For example if we have a login feature and a registration feature. So in registration, the developer changed the criteria for the password. in regression testing, we had previous users who created their profiles with a password that contained only one or two digits. 

What will happen with these Users. Will they access the system? Or would we send them a notification telling them that they must change their password?

So in this case I will test the login functionality. I will also test edit profile functionality if the user edits his profile can be edit it and add a password.That's why sometimes we need automation testing. We must automate a lot of test cases so that we can cover regression testing.



## :100:9.Smoke Testing

When the developer changes a feature should we test the whole application? Sometimes we don't have time to do this so what shall we do?

==The most basic functionalities are in the software. The result of this testing is used to decide if a build is stable enough to proceed with further testing.==

Before beginning our test cases we perform the smoke testing. If the smoke testing passes, then we can perform functional testing, non-functional testing and all other types of testing. If this testing fails then we return the build to the developer.



-------------------------------------------------



# :two:Test Scenario Writing

## Test scenario

Any functionality that can be tested.We also call it a test condition or a test possibility.

You should put yourself in the end user shoes and figure out the real-world scenarios and use cases of the application under test.

For example, I'm testing registration page. What are the scenarios that the user is expected to go through?



**One monile application registration test scenarios**

![1679014512251](README.assets/1679014512251.png)



![1679018525850](README.assets/1679018525850.png)

![1679018542212](README.assets/1679018542212.png)



**KFC Registration Test Scenarios**  

![1679027686022](README.assets/1679027686022.png)

![1679027704858](README.assets/1679027704858.png)





**Facebook Sign-up Test **

![1679029400891](README.assets/1679029400891.png)



![1679033934484](README.assets/1679033934484.png)

![1679033963931](README.assets/1679033963931.png)

![1679033993744](README.assets/1679033993744.png)

![1679034007493](README.assets/1679034007493.png)





**Facebook Login Test Scenarios**

![1679034299585](README.assets/1679034299585.png)



##:100: Invalid email address login and registration?

==In the registration invalid email address means that this email has a wrong format or it is already used.==

 ==In the login form, the invalid email means this email is not registered to the website==



![1679035639387](README.assets/1679035639387.png)

![1679035664996](README.assets/1679035664996.png)



**The search functionality**

![1679036545692](README.assets/1679036545692.png)







# :three:Test Case Writing

##What is test case？

A set of preconditions, inputs, actions (where applicable), expected results 
and postconditions, developed based on test conditions.

![1679189407950](README.assets/1679189407950.png)



### 1.Test Case Title

![1679189558225](README.assets/1679189558225.png)



### 2.Precondition

**Must be met before testing**

![1679189664252](README.assets/1679189664252.png)



###3.Test Steps

**The steps that will be required to execute this test case, and these steps must be very clear and informative.**

![1679189761151](README.assets/1679189761151.png)



### 4.Excepted result

**When the user enters a valid user name, enters a valid password, clicks on sign in. What would happen?**

![1679190284358](README.assets/1679190284358.png)



### 5.Test Scenarios(Test Suite)

**It will be inside a folder or inside a section which is the module or the test suite which is in this case log in. We can have a test suite which is called log in or we can have more than one test suite, one for Login with Facebook one for log in with gmail, one for log in using username. It depends on the size of the project. If the project is small we can add all the login test cases inside one test suite. If we have a big project we can divide them into more than one test suite.**

![1679190426462](README.assets/1679190426462.png)



### 6.Test Environment

- The hardware

  What is the device that I will test this test case on?

- The software

  Operation system : windows 10...

- The network

  WI-FI/Mobile data

![1679190611971](README.assets/1679190611971.png)



### 7.Actual Result

**After executing the test case. You should write the field and leave it empty!**

![1679190872431](README.assets/1679190872431.png)



### 8.Status

![1679191104233](README.assets/1679191104233.png)

**Blocked/Skipped : Because I am not able to test it. Why I'm not able to test the login functionality ?because it depends on the registration functionality.**



![1679191149146](README.assets/1679191149146.png)





# :100:Test case VS test scenarios

Test cases are derived from test scenarios.

A test scenario is a single statement (description) describing a specific functionality in the application.~测试场景是描述应用程序中特定功能的单个语句（描述）。~

Test cases contain definite a description, test steps, data, and expected results for testing this is specific functionality. ~测试用例包含明确的描述、测试步骤、数据和测试特定功能的预期结果~





## Example Sign-up test case

![1679197863703](README.assets/1679197863703.png)

![1679197910929](README.assets/1679197910929.png)



## Invalid scenarios

###what are invalid test cases?

==These are the test cases that include an error or a mistake. So the user made a mistake in using the software.==

- For example you can click on sign up without choosing admin or project owner.
- You can click and sign up without entering a username or without entering an email or without entering a password.

### Invalid username

#### 1.only one character

#### 2.Already used username 

#### 3.long username

#### 4.empty username

#### 5.localization different language.

![1679199781468](README.assets/1679199781468.png)





### Invalid email

####1.Already used email

#### 2.Empty email

#### 3.Wrong email format

#### 4.Already registered but not verify

#### 5.Email is attached with Facebook

####6.Email is attached with Gmail

![1679202380475](README.assets/1679202380475.png)





###Invalid password

#### 1.Empty password

#### 2.Less than 6 characters

#### 3.Not contain numbers (alphanumeric)

####4.Not contain special character

####5.Not begin with a capital letter

![1679203400302](README.assets/1679203400302.png)

