# T1A1-Workbook-B
---

## Question 1: Describe the architecture of a typical Flask application
---


&nbsp;

## Question 2: Identify a database management system (DBMS) commonly used in web applications (including Flask) and discuss the pros and cons of this database
---
 *An example of a database management system (DBMS) that is commonly used in web applications is PostgreSQL. PostgreSQL is an open source object-relational database system that utilizes Structured Query Language (SQL). PostgreSQL has been in development for over 30 years and is backed by a highly experienced community of developers. On top of having a long history of development, PostgreSQl is compatible with many modern programming languages such as Java, Python, C, Ruby, PHP and PERL.*


## Pros:
- <strong>Open Source:</strong> 

    PostgreSQL's source code is freely available to anyone that would like to use it.  This allows for it be modified as needed for each specific use-case. 

- <strong>Reliability:</strong> 
    
    PostgreSQL had been in development for over 30 years. In this time, many companies and professionals have contributed to the project, so its current state is the culmination of 25 years of innovation driven by those that actively use it. PostgreSQL has a passionate community behind it which continuously looks for improvements and fixes for bugs.

- <strong>Scalability:</strong> 

    PostgreSQL is excellent for those that look to expand in the future.  It allows for vertical scaling, meaning that its performance will increase the more resources that you make available to it.

- <strong>Extensibility:</strong> 
    1. Compatible with many languages (Java, Python, C, Ruby, PHP and PERL)
    2. Many extensions are available to provide additional functionality.
    3. Code is open source, so it can be modified for individual needs.
    4. Supports a large variety of data types (boolean, character, numeric, temporal, UUID, array, JSON, hstore).

## Cons:

- <strong>Slower Speed:</strong> 

    PostgreSQL is slower than MySQL on many performance metrics.  Changes made to improve speed performance also require more work.

- <strong>Installation Difficulty:</strong> 

    Installation and configuration of PostgreSQL can be more difficult for beginners.

- <strong>Documentation:</strong> 

    Expandable documentation is only available in English. Some fo the documentation is often incomplete which may cause delays when troubleshooting.
 

## Question 3: Discuss the implementation of Agile project management methodology
---

*Agile project management is an iterative approach to developing software. This methodology focuses heavily on incremental steps rather than following a linear path which allows for the process to become more adaptable and promotes faster development.  The iterative approach facilitates the incorporation of customer feedback throughout the development process which leads to a more complete development process with less backtracking.*

### Below are steps that should be taken for implementing Agile project management:
<br>

- <strong>Planning Meeting:</strong>

    The first step to Agile implementation is to hold a meeting to make the goals and the steps to achieve those goals as clear as possible.  Everyone involved should leave the meeting with a clear cut idea of what the project is trying to accomplish and where they should begin to reach the goal. The meeting should include all relevant members of the business (stakeholders, owners, product team members) so that everybody, from the top down, can see the mission clearly. 

- <strong>Road Map Construction:</strong>

    Now that an overall strategy is in place from the initial planning meeting, a product road map must be created that reflects the goals discussed. The road map does not have to be in perfect detail, instead it should represent a rough overview of the goals.  This overview should contain details for each goal, including dates, time estimations, features, and metrics. The general road map should be the responsibility of the project owner, but should include the input from representatives of all teams involved so that it is as accurate as possible. 

- <strong>Release Plan:</strong>

    After the road map is in place, a timetable should be created by the owner that outlines the planned time for each release. Features on this timetable should be prioritized based on how important they are for the initial release. This means that all essential features should be given attention initially, followed by other high-priority features after launch. 

- <strong>Sprint Timeline:</strong>

    The next step for successful implementation of Agile project management is sprint planning. This is where the planning process shifts from general planning to more specific planning. Sprint planning should be carried out by the development team in collaboration with the project owner and managers.  Each sprint cycle should set specific dates for when each sprint will end and set goals that are achievable during that time period.  Once the planning process for the sprint is done, the development team should have a clear goal and know each member's role in achieving it. 

- <strong>Daily Standups:</strong>

    Now that the team has a clear cut goal and timeline, daily standups should be utilized to keep the team engaged and in the loop for how the feature is progressing. Standups are short meetings in which each member discusses what they have completed, what they are working on, and any roadblocks they may have encountered. Daily standups are essential in facilitating team communication and collaboration. 

- <strong>Sprint Review:</strong> 

    After each sprint, a sprint review should take place.  This meeting is a chance for the development team to showcase what was accomplished during the last sprint and update what needs to still be done.  Sprint reviews should include the product owner and relevant stake holders so that feedback can be provided.  Sprint reviews are meant to foster collaboration and keep all members on the same page regarding what has been accomplished. 

- <strong>Sprint Retrospective:</strong> 

    The final step in the process is the sprint retrospective. This is a meeting held to discuss what went well and what needs to be improved upon during the previous sprint cycle. 

## Question 4: Provide an overview and description of a standard source control workflow
---

*The following overview and description is based on the Git Feature Branch Workflow.*

### <strong>Overview</strong>

Git Feature Branch Workflow is excellent for allowing multiple developers to work on a feature without causing issues on the main branch of code. The idea behind it is that developers create a new branch every time they begin working on a new feature. These branches are identical to the main branch of code, so the features in development will behave just as if they were on the main branch of code.  This allows for developers to work without the worry of breaking the main branch and helps ensure that the main branch never contains any broken code. 

### <strong>Description</strong>
*Below is a simple example of a Git Feature Branch Workflow.*

1. The project is cloned.

    ``` git clone git@github.com:DTjomsland/firstrepo.git ```

2. Now that the project is cloned, a branch must be made for the feature that is in development.

    ``` git checkout -b best_feature_ever ```

3. Code additions and commits are made.

    ``` git commit -m "Final commit for feature" ```

4. The feature branch then can be pushed to the repository without modifying the main branch.

    ``` git push origin best_feature_ever ```

5. The code can now be reviewed and checked for errors.

6. A merge request is created to combine the feature with the main branch. The team lead then reviews the code and it is merged to the main branch.



## Question 5: Provide an overview and description of a standard software testing process
---
*The following overview and description is based on standard software testing process of manual testing.*

### <strong>Overview</strong>

Manual testing is the most basic form of software testing that is done without the help of any automation, meaning the test cases are executed manually by the tester. In manual testing, the actual behavior of the program is compared to the intended behavior.  If their is any difference between the two, the difference is reported as an error.  For example, a developer creates a purchase option for an item and needs to test it to make sure it is functioning properly. The intended result is for the purchase button to take the user to the payment page, but instead the button refreshes and stays on the same page.  This would be reported as an error because it did not work as intended.

#### Stages of Manual Testing:

1. <strong>Unit Testing:</strong>

    A unit is the smallest testable part of a program.  Unit testing involves going through these units and making sure each of them are functioning as intended.  This This is often carried out in the early stages of development in order to help the developers find and fix initial bugs. An example of this is testing individual functions to see if they return the proper data. 

2. <strong>Integration Testing:</strong>

    Integration testing is the testing of multiple integrated units.  This allows the developers to know whether select units are functioning together properly.  This too is done during development in order to catch bugs early on. 

3. <strong>System Testing:</strong>

    System testing is the testing of all of the integrated modules as a whole. This is a the way for a QA team to evaluate how all of the modules interact with with each other in the full system/application. This is where it is verified if the product performs all of the intended tasks and meets all of the requirements of the business. Often included in this are tests for performance and user experience.

4. <strong>UI Testing:</strong>

    UI testing includes tests to ensure all components of a User Interface are functioning properly.  For example, text fields, buttons, and interactive features.  The focus of user interface testing often includes testing for usability, performance, and functionality. This stage of testing is incredibly important due to the fact that a flawed UI often deters users from returning.

5. <strong>Acceptance Testing:</strong>

    The goal of acceptance testing is to make sure the entire system  functions properly during real world use. Often included in acceptance testing are Alpha and Beta releases of the product.  Alpha testing is where the product is used by the company internally to test for defects.  Beta testing is where the product is released to a select amount of external users to give feedback and report bugs.  Accessibility testing for those with disabilities is often included in this step to ensure the project is inclusive. 




## Question 6: 	Discuss and analyse requirements related to information system security and how they relate to the project (Cyber attacks)
---

Information System Security (INFOSEC) encompasses the protection of computers, networks, and the data they contain. Technological advancements are expanding rapidly, and with these advancements more and more data is being store over networks.  These wide networks often contain confidential data for both users and companies which must be kept safe from unauthorized users who intend to access and misuse it.  ACME must prioritize Information System Security to uphold the three tiers of the CIA triangle: *Confidentiality*, *Integrity*, and *Availability*.

<br>

<strong>Confidentiality:</strong>

The main aspect of confidentiality is ensuring that only authorized users are allowed to access systems and data that contain sensitive information. This can be upheld through the use of authorization every time an authorized user attempts to access sensitive information. Security measures must implemented in order to limit the access to sensitive to those that need it to complete their tasks.  

<br>

<strong>Integrity:</strong>

The goal of integrity is to keep information accurate and consistent, only allowing changes to be made by those that are authorized. Integrity is considered to be maintained when information remains intact and unchanged throughout its usage, storage and transmission. Integrity can be compromised in a multiple ways, the two most common being intentional and unintentional manipulation. Intentional manipulation includes an individual modifying data with malicious intent.  Unintentional manipulation includes an authorized user accidentally deleting or modifying important data.  Integrity can be maintained by only allowing personnel that are both authorized and experienced access to modify data.

<br>

<strong>Availability:</strong>

In order to uphold the availability tier, it must be ensured that access to information is only allowed during specified time frames. Allowing access only during specified time frames promotes further limitations to the accessibility of sensitive information.  Availability can be maintained by implementing measures, such as, only allowing access during working hours with limited exceptions.

<br>

### <strong>INFOSEC Recommendations for AMCE Corporation:</strong>

- <strong>Authentication:</strong>

    Multi-factor authorization should be implemented to ensure only authorized users are allowed to modify sensitive data.  
    
    *Example: Combination of ID, password, and biometric data*

- <strong>Access Control:</strong>

    Allow personnel access to information relevant to the task that they need to complete and nothing more. 

    *Example: Access Control List or a Role Based Control List.*


- <strong>Encryption:</strong>

    Encryption of transferred data must be made a priority.  Encryption prevents unauthorized individuals from receiving or intercepting readable data.

    *Example: Follow AES(Advanced Encryption Standard) or DES (Data Encryption Standard).*

<br>
<br>

## Question 7: 	Discuss common methods of protecting information and data and how you would apply them to the project
---

*There are many common methods available to protect information and data for ACME Corporation.  Below is a list with descriptions of possible methods that could help secure ACME Corporations sensitive Data.*

### Common Methods of Data and Information Protection:

- <strong>Access Controls:</strong>
    
    Access Controls involve limiting the access to sensitive data and systems, both physically and digitally.  Included in this is ensuring that all company devices are ID and password protected and that only authorized personnel are allowed to come into physical contact with devices that either store or access sensitive data.


- <strong>Authentication:</strong>

    Authentication is the process by which someone is verified to be who they claim to be.  The most methods for authentication can be broken up into three groups: something you are, something you have, and something you know.  Something you are is the strongest of the three. This includes using biometric data such as fingerprints or retina scans in order to verify someones identity.  Something you have includes token generators which can be provided through both smart phones and token devices.  These are every hard to gain unauthorized access too because the tokens are constantly changing and need to be entered within a certain time frame. Something you know includes passwords.  Passwords must be unique and hard to guess to ensure the protection of sensitive data.

- <strong>Backups:</strong>

    A backup is an additional copy of data that is stored safely in case the original is the target of a malicious attack or unintentional manipulation. Backups are crucial to ensuring the integrity of data.   Backups for ACME Corporation should be stored in a separate location, both physically and virtually, from the original data.  This will ensure that data in both locations cannot be manipulated at the same time.

- <strong>Encryption:</strong>

    Encryption is the use of an algorithm to transform readable text into ciphertext.  Encrypted text cannot be read unless an encryption key is used to decrypt the data. With the advent of cloud data and security breaches becoming more and more prevalent, it is recommended that the bulk of all sensitive data including, but not limited to, stored data and email communications, be encrypted to ensure its integrity.

- <strong>Data Erasure:</strong>

    Data erasure is the deletion of old and unused data.  This practice ensures that unused and old data is permanently destroyed in order to prevent a security breach.  A common scenario in which it is utilized is after the the retirement of old equipment. To render data completely unrecoverable, it must be overwritten, not just deleted.  In order to ensure all sensitive data is completely deleted, proper measures must be taken such as the utilization of reputable software or a company that specializes in complete data removal.


<br>
<br>

## Question 8: 	Research what your legal obligations are in relation to handling user data and how they can be met for the project
---

The Privacy Act 1988 (Privacy Act) is what regulates how a user's personal information is handled by application developers. What constitutes personal information can often vary, but includes contact lists, IP Addresses, Unique Device Identifiers, biometric and voice data, location information and payment information. Within the Privacy Act are Australian Privacy Principles (APPS) which provide an excellent guideline for the collection, use, disclosure and storage of personal information. The thirteen Australian Privacy Principles are as follows:

<br>

### Australian Privacy Principles

<br>

- <strong>Part One:  Consideration of Personal Information Privacy</strong>

    1. Open and Transparent Management of Personal Information
    2. Anonymity and Pseudonymity

    <br>

- <strong>Part Two: Collection of Personal Information</strong>

    3. Collection of Solicited Personal Information
    4. Dealing With Unsolicited Personal Information
    5. Notification of the Collection of Personal Information

    <br>

- <strong>Part Three: Dealing with Personal Information</strong>

    6. Use or Disclosure of Personal Information
    7. Direct Marketing
    8. Cross-border Disclosure of Personal Information
    9. Adoption, Use or Disclosure Of Government Related Identifiers

    <br>

- <strong>Part Four: Integrity of Personal Information</strong>

    10. Quality of Personal Information
    11. Security of Personal Information

   <br>

- <strong>Part Five:  Access to, and correction of, personal information</strong>

    12. Access to Personal Information
    13. Correction of Personal Information

<br>
<br>

### <strong>Upholding the thirteen Australian Privacy Principles at ACME Corporation:</strong>

<br>

<strong>Part One:  Consideration of Personal Information Privacy</strong>

Acme Corporation must manage all personal information in a transparent way.  Personal information includes all information or opinions about a reasonably identifiable individual. This can be achieved by having clear procedures when handling personal information. ACME Corporation must also provide the option for individuals to not identify themselves or use a pseudonym. 

<br>

<strong>Part Two: Collection of Personal Information</strong>

Acme Corporation must take extreme caution when collecting personal information and ensure that all sensitive information is gathered with the consent of the user. When sensitive data is collected, ACME Corporation must notify the individual that the information ahs been collected and inform them why and whether it may be disclosed. In order to 

 <br>

<strong>Part Three: Dealing with Personal Information</strong>

<br>

<strong>Part Four: Integrity of Personal Information</strong>

<br>

- <strong>Part Five:  Access to, and correction of, personal information</strong>


## Question 9: 	Describe the structural aspects of the relational database model. Your description should include information about the structure in which data is stored and how relations are represented in that structure.
---

<br>
<br>

## Question 10: Describe the integrity aspects of the relational database model. Your description should include information about the types of data integrity and how they can be enforced in a relational database.
---

<br>
<br>

## Question 11: Describe the manipulative aspects of the relational database model. Your description should include information about the ways in which data is manipulated (added, removed, changed, and retrieved) in a relational database.
---

<br>
<br>

## Question 12: Conduct research into a web application (app) and answer the following parts:  
  a. List and describe the software used by the app.
  b. Describe the hardware used to host the app.
  c. Describe the interaction of technologies within the app
  d. Describe the way data is structured within the app
  e. Identify entities which must be tracked by the app
  f. Identify the relationships and associations between the entities you have identified in part (e)
  g. Design a schema using an Entity Relationship Diagram (ERD) appropriate for the database of this website (assuming a relational database model)
---