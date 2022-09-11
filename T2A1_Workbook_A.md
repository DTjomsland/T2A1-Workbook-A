# T1A1-Workbook-B
---

## Question 1: Describe the architecture of a typical Flask application
---

*Flask is a Python module that streamlines the development of web applications. Considered to be a micro web framework, it is incredibly small and bare-boned.  It is not shipped with a plethora of features built in, instead, it is up to the developer to decide which features will be used.  These features are added in the form of extensions, which are numerous and able to solve just about any problem a web developer could face.  The following is based on ACME Corporations request for a Flask Web Application.*

<br>

### <strong>Flask Web Application Architecture</strong>

<br>
<strong>Basics:</strong>

The basics of a Flask web application consist of the following, client-side code and server-side code. Client-side code is the code that the browser interprets and that the user interacts with.  The server-side code is the code that is stored on that server that responds to the HTTP requests sent by the client-side code. Client-side code often consists of three languages, HTML, CSS, and JavaScript.  These are all interpreted by the browser and interacted with by the user.  Server-side code in this instance is Python using the Flask framework. The Flask framework is responsible for creating the requested page as well as storing data such as user information and user input. 

<br>

<strong>Components of a Flask Web Application:</strong>

<strong>Presentation Layer: </strong>

This is the client-side code that was mentioned before.  Usually consisting of HTML, CSS, and JavaScript, the presentation layer is what the browser renders and the user interacts with.  This code resides in the browser and presents the user with an interface containing their requested information.

<strong>Business Logic Layer: </strong>

This is the server-side code that is responsible for data exchange.  It takes in requests from the presentation layer and applies business logic to them in order to decide how to process the data.  In the case of a Flask application, this is done by the Controllers.

<strong>Data Service Layer: </strong>

The purpose of the data service layer is to transmit data that was processed by the Business Logic layer back to the Presentation layer. This layer also ensures the security of all information passed between the two layers. 

<strong>Data Access Layer: </strong>

The data access layer is what facilitates access to data-stored in persistent storage, such as a relational database. This is the layer that performs CRUD operations and returns stored data to the business layer. In a Flask application, this is handled by models, which is python code that interacts with the database.  A popular toolkit used for this layer is SQLAlchemy that facilitates communication between Python programs and SQL databases. 

<br>









## Question 2: Identify a database management system (DBMS) commonly used in web applications (including Flask) and discuss the pros and cons of this database
---
 *An example of a database management system (DBMS) that is commonly used in web applications is PostgreSQL. PostgreSQL is an open source object-relational database system that utilizes Structured Query Language (SQL). PostgreSQL has been in development for over 30 years and is backed by a highly experienced community of developers. On top of having a long history of development, PostgreSQl is compatible with many modern programming languages such as Java, Python, C, Ruby, PHP and PERL.*


## Pros:
- <strong>Open Source:</strong> 

    PostgreSQL's source code is freely available to anyone that would like to use it.  This allows for it to be modified as needed for each specific use-case. 

- <strong>Reliability:</strong> 
    
    PostgreSQL has been in development for over 30 years. In this time, many companies and professionals have contributed to the project, so its current state is the culmination of 25 years of innovation driven by those that actively use it. PostgreSQL has a passionate community behind it which continuously looks for improvements and fixes for bugs.

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

    Expandable documentation is only available in English. Some for the documentation is often incomplete which may cause delays when troubleshooting.
 

## Question 3: Discuss the implementation of Agile project management methodology
---

*Agile project management is an iterative approach to developing software. This methodology focuses heavily on incremental steps rather than following a linear path which allows for the process to become more adaptable and promotes faster development.  The iterative approach facilitates the incorporation of customer feedback throughout the development process which leads to a more complete development process with less backtracking.*

### Below are steps that should be taken for implementing Agile project management:

<br>

- <strong>Planning Meeting:</strong>

    The first step to Agile implementation is to hold a meeting to make the goals and the steps to achieve those goals as clear as possible.  Everyone involved should leave the meeting with a clear cut idea of what the project is trying to accomplish and where they should begin to reach the goal. The meeting should include all relevant members of the business (stakeholders, owners, product team members) so that everybody, from the top down, can see the mission clearly. 

<br>

- <strong>Road Map Construction:</strong>

    Now that an overall strategy is in place from the initial planning meeting, a product road map must be created that reflects the goals discussed. The road map does not have to be in perfect detail, instead it should represent a rough overview of the goals.  This overview should contain details for each goal, including dates, time estimations, features, and metrics. The general road map should be the responsibility of the project owner, but should include the input from representatives of all teams involved so that it is as accurate as possible. 

<br>

- <strong>Release Plan:</strong>

    After the road map is in place, a timetable should be created by the owner that outlines the planned time for each release. Features on this timetable should be prioritized based on how important they are for the initial release. This means that all essential features should be given attention initially, followed by other high-priority features after launch. 

<br>

- <strong>Sprint Timeline:</strong>

    The next step for successful implementation of Agile project management is sprint planning. This is where the planning process shifts from general planning to more specific planning. Sprint planning should be carried out by the development team in collaboration with the project owner and managers.  Each sprint cycle should set specific dates for when each sprint will end and set goals that are achievable during that time period.  Once the planning process for the sprint is done, the development team should have a clear goal and know each member's role in achieving it. 

<br>

- <strong>Daily Standups:</strong>

    Now that the team has a clear cut goal and timeline, daily standups should be utilized to keep the team engaged and in the loop for how the feature is progressing. Standups are short meetings in which each member discusses what they have completed, what they are working on, and any roadblocks they may have encountered. Daily standups are essential in facilitating team communication and collaboration. 

<br>

- <strong>Sprint Review:</strong> 

    After each sprint, a sprint review should take place.  This meeting is a chance for the development team to showcase what was accomplished during the last sprint and update what needs to still be done.  Sprint reviews should include the product owner and relevant stakeholders so that feedback can be provided.  Sprint reviews are meant to foster collaboration and keep all members on the same page regarding what has been accomplished. 

<br>

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

Manual testing is the most basic form of software testing that is done without the help of any automation, meaning the test cases are executed manually by the tester. In manual testing, the actual behavior of the program is compared to the intended behavior.  If there is any difference between the two, the difference is reported as an error.  For example, a developer creates a purchase option for an item and needs to test it to make sure it is functioning properly. The intended result is for the purchase button to take the user to the payment page, but instead the button refreshes and stays on the same page.  This would be reported as an error because it did not work as intended.

#### Stages of Manual Testing:

1. <strong>Unit Testing:</strong>

    A unit is the smallest testable part of a program.  Unit testing involves going through these units and making sure each of them are functioning as intended.  This  is often carried out in the early stages of development in order to help the developers find and fix initial bugs. An example of this is testing individual functions to see if they return the proper data. 

2. <strong>Integration Testing:</strong>

    Integration testing is the testing of multiple integrated units.  This allows the developers to know whether select units are functioning together properly.  This too is done during development in order to catch bugs early on. 

3. <strong>System Testing:</strong>

    System testing is the testing of all of the integrated modules as a whole. This is the way for a QA team to evaluate how all of the modules interact with each other in the full system/application. This is where it is verified if the product performs all of the intended tasks and meets all of the requirements of the business. Often included in this are tests for performance and user experience.

4. <strong>UI Testing:</strong>

    UI testing includes tests to ensure all components of a User Interface are functioning properly.  For example, text fields, buttons, and interactive features.  The focus of user interface testing often includes testing for usability, performance, and functionality. This stage of testing is incredibly important due to the fact that a flawed UI often deters users from returning.

5. <strong>Acceptance Testing:</strong>

    The goal of acceptance testing is to make sure the entire system  functions properly during real world use. Often included in acceptance testing are Alpha and Beta releases of the product.  Alpha testing is where the product is used by the company internally to test for defects.  Beta testing is where the product is released to a select amount of external users to give feedback and report bugs.  Accessibility testing for those with disabilities is often included in this step to ensure the project is inclusive. 




## Question 6: 	Discuss and analyse requirements related to information system security and how they relate to the project (Cyber attacks)
---

Information System Security (INFOSEC) encompasses the protection of computers, networks, and the data they contain. Technological advancements are expanding rapidly, and with these advancements more and more data is being stored over networks.  These wide networks often contain confidential data for both users and companies which must be kept safe from unauthorized users who intend to access and misuse it.  ACME must prioritize Information System Security to uphold the three tiers of the CIA triangle: *Confidentiality*, *Integrity*, and *Availability*.

<br>

<strong>Confidentiality:</strong>

The main aspect of confidentiality is ensuring that only authorized users are allowed to access systems and data that contain sensitive information. This can be upheld through the use of authorization every time an authorized user attempts to access sensitive information. Security measures must be implemented in order to limit the access to sensitive data to those that need it to complete their tasks.  

<br>

<strong>Integrity:</strong>

The goal of integrity is to keep information accurate and consistent, only allowing changes to be made by those that are authorized. Integrity is considered to be maintained when information remains intact and unchanged throughout its usage, storage and transmission. Integrity can be compromised in multiple ways, the two most common being intentional and unintentional manipulation. Intentional manipulation includes an individual modifying data with malicious intent.  Unintentional manipulation includes an authorized user accidentally deleting or modifying important data.  Integrity can be maintained by only allowing personnel that are both authorized and experienced access to modify data.

<br>

<strong>Availability:</strong>

In order to uphold the availability tier, it must be ensured that access to information is only allowed during specified time frames. Allowing access only during specified time frames promotes further limitations to the accessibility of sensitive information.  Availability can be maintained by implementing measures, such as, only allowing access during working hours with limited exceptions.

<br>

### <strong>INFOSEC Recommendations for ACME Corporation:</strong>

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

<br>

*There are many common methods available to protect information and data for ACME Corporation.  Below is a list with descriptions of possible methods that could help secure ACME Corporations sensitive Data.*

### Common Methods of Data and Information Protection:

- <strong>Access Controls:</strong>
    
    Access Controls involve limiting the access to sensitive data and systems, both physically and digitally.  Included in this is ensuring that all company devices are ID and password protected and that only authorized personnel are allowed to come into physical contact with devices that either store or access sensitive data.


- <strong>Authentication:</strong>

    Authentication is the process by which someone is verified to be who they claim to be.  The most methods for authentication can be broken up into three groups: something you are, something you have, and something you know.  Something you are is the strongest of the three. This includes using biometric data such as fingerprints or retina scans in order to verify someone's identity.  Something you have includes token generators which can be provided through both smartphones and token devices.  These are very hard to gain unauthorized access too because the tokens are constantly changing and need to be entered within a certain time frame. Something you know includes passwords.  Passwords must be unique and hard to guess to ensure the protection of sensitive data.

- <strong>Backups:</strong>

    A backup is an additional copy of data that is stored safely in case the original is the target of a malicious attack or unintentional manipulation. Backups are crucial to ensuring the integrity of data.   Backups for ACME Corporation should be stored in a separate location, both physically and virtually, from the original data.  This will ensure that data in both locations cannot be manipulated at the same time.

- <strong>Encryption:</strong>

    Encryption is the use of an algorithm to transform readable text into ciphertext.  Encrypted text cannot be read unless an encryption key is used to decrypt the data. With the advent of cloud data and security breaches becoming more and more prevalent, it is recommended that the bulk of all sensitive data including, but not limited to, stored data and email communications, be encrypted to ensure its integrity.

- <strong>Data Erasure:</strong>

    Data erasure is the deletion of old and unused data.  This practice ensures that unused and old data is permanently destroyed in order to prevent a security breach.  A common scenario in which it is utilized is after the retirement of old equipment. To render data completely unrecoverable, it must be overwritten, not just deleted.  In order to ensure all sensitive data is completely deleted, proper measures must be taken such as the utilization of reputable software or a company that specializes in complete data removal.


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

- <strong>Part Five:  Access to, and Correction of, Personal Information</strong>

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

Acme Corporation must take extreme caution when collecting personal information and ensure that all sensitive information is gathered with the consent of the user. When sensitive data is collected, ACME Corporation must notify the individual that the information has been collected and inform them why and whether it may be disclosed. 

 <br>

<strong>Part Three: Dealing with Personal Information</strong>

Acme Corporation must be diligent in the way it uses or discloses information as well. Personal information must be only used in ways that the users would expect, meaning that if information is gathered for one purpose, the user must consent for it to be used in a different way. ACME Corporation must also refrain from using personal information for direct marketing, unless permission is given by the user.

<br>

<strong>Part Four: Integrity of Personal Information</strong>

ACME Corporation must take all necessary steps to ensure the accuracy of user information. To achieve this, ACME Corporation  should remind their users to update personal information with every purchase, contact users to retrieve updated information, and consistently update their information so it is as complete and accurate as possible. 

<br>

<strong>Part Five:  Access to, and Correction of, Personal Information</strong>

ACME Corporation must ensure that users have access to their personal information that the company stores.  In order to be given access, their identities should be verified so proper verification measures should be in place.   Users must also be able to update or correct their personal information either by themselves, or through the help of a company representative. These measures will help ensure that all stored information is as safe and accurate as possible. 

<br>

<br>

## Question 9: 	Describe the structural aspects of the relational database model. Your description should include information about the structure in which data is stored and how relations are represented in that structure.
---

*A Relational Database Model is a representation of how data is stored in Relational Databases. Relational Databases utilize tables that are made up of columns and rows to organize data.  This data can come in a variety of forms including strings, arrays, characters, booleans, integers, and varchar.*

<br>

<strong>Table Structure</strong>

Data in the relational Database Model is typically stored across multiple tables.  These tables represent an entity and consist of data that is related in some way.  Each table is made up of one or more *columns* which are assigned a specific data type (ex: string, integer). Columns represent a set of values for a particular attribute. *Rows* in a database represent a data record.  Each row in a database represents a complete record of an item and is commonly referred to as a *tuple*. For example, a table containing data on Student Information may have columns that consist of STUDENT_ID, NAME, ADDRESS, AGE, and PHONE_NUMBER.  Each of these columns are assigned a different data type so that they are all uniform. Each row in this table creates a complete record of each student, containing multiple types of data. (Example below)

<br>


### <strong>Student:</strong>

|Student_ID   	| Name  	|  Address 	|  Age 	|   Phone_Number	|
|---	|---	|---	|---	|---	|
|  1 	| Frank  	| Perth  	| 25  	|  555555555 	| 
|  2 	| Jose  	| New York  	| 28  	|  666666666 	|
|  3 	| Sandra  	| Perth 	| 21  	|  888888888 	|
|  4 	| Dan 	| Boston 	| 32 	|  999999999 	|

<br>

A *relational schema* is a representation of the name of a relation with its attributes. In the case of the previous table, the relation schema would be STUDENT (Student_ID, Name, Address, Age and Phone_Number).  The purpose of a relational schema is to describe how data is structured within tables.

<br>

<strong>Primary and Foreign Keys</strong>

*Primary keys* are used to ensure that data is unique in a specific column. In the example above, the primary key is Student_ID.  Primary keys cannot have repetition or be given NULL values.  The use of primary keys allows for information from one table to be linked to another table.  When a primary key from one table is used in another, it is considered a *foreign key*. A foreign key is a column in one table that represents a column in another table. In the example below, the primary key from the above Student table is used as a foreign key to link the two tables. 

<br>

### <strong>Classes:</strong>

|Student_ID   	| Course_Name 	| 
|---	|---	|
|  1 	| Web Development 	|
|  2 	| Web Development 	|
|  4	| Web Development   	|
|  3 	| Database Management	|
|  4 	| Database Management	|

(Typically, foreign keys would be used for the course names to avoid repetitive data.)
<br>
<br>

## Question 10: Describe the integrity aspects of the relational database model. Your description should include information about the types of data integrity and how they can be enforced in a relational database.
---

<br>
Data integrity in regards to a relational database is the accuracy, consistency, and completeness of data within the database. It also refers to the safety of the data within the database and the security and safety measures that are implemented to ensure that it remains accurate and complete. Data integrity is maintained through the use of rules, standards and processes that are often implemented as early as the design phase.  There are four types of data integrity that must be enforced in a relational database that include entity integrity, referential integrity, domain integrity, and user-defined integrity.  Below is an overview of each type.

<br>

<strong>Entity Integrity:</strong>

This relies on the creation of primary keys to ensure that data within the database is not redundant and that none of the fields are null. This rule declares that every table should have its own primary key and that each key must be unique.

<br>

<strong>Referential Integrity:</strong>

This relies on the concept of foreign keys to ensure that data is stored and used uniformly. The database's structure should have rules embedded that regard how foreign keys are utilized to ensure that appropriate data modifications occur, such as changes, deletions, or insertions. These rules may include constraints to 
remove the possibility of duplicate data, guarantee data accuracy, and ensure data that doesn't apply is not entered.

<br>

<strong>Domain Integrity:</strong>

This refers to the acceptable types of values a column in a database is able to contain. It includes constraints to ensure that only the proper/designated datatype is used in a particular column. For instance, if an Age(integer) is entered into a column that is supposed to only contain (Names)strings, an error should be given and prevent it from happening. 

<br>

<strong>User-defined Integrity:</strong>

This refers to any rules or constraints that the user has created in order to fit their specific needs. Depending on the use-case, referential, domain integrity might not be enough to mee the companies needs, so they integrate their very own integrity measures.

<br>
<br>

## Question 11: Describe the manipulative aspects of the relational database model. Your description should include information about the ways in which data is manipulated (added, removed, changed, and retrieved) in a relational database.
---

<br>

Manipulation of a database is typically done by a data manipulation language (DML).  Data manipulation languages are computer programming languages that allow for data to be added, removed, changed and retrieved. A common DML used for the manipulation of a relational database is Structured Query Language (SQL). SQL consists of data change statements which allow for the modification of stored data, but not the objects or the schema of the database. Below are examples of how data is added, removed, changed, and retrieved in a relational database using SQL. The table below will be used as a starting point for each modification. 

<br>

### <strong>Students</strong>

|Student_ID   	| Name  	|  Address 	|  Age 	|   Phone_Number	|
|---	|---	|---	|---	|---	|
|  1 	| Frank  	| Perth  	| 25  	|  555555555 	| 
|  2 	| Jose  	| New York  	| 28  	|  666666666 	|
|  3 	| Sandra  	| Perth 	| 21  	|  888888888 	|
|  4 	| Dan 	| Boston 	| 32 	|  999999999 	|

<br>



<strong>Adding Data:</strong>

The INSERT statement is used to add new rows to a table within a relational database. For every new row of data, a new INSERT statement must be created. The desired values to be entered must be separated by commas and need to be in the same order as the columns appear in the database. The syntax used to achieve this is as follows:

    INSERT INTO table [(column [, column...])] VALUES (value [, value...]);

If we want to add a new row to the table above, we would use the following statement:

    INSERT INTO Students (Student_ID,Name,Address,Age,Phone_Number) VALUES (5, 'Lisa', 'Houston', 40, 333333333);

The outcome of the previous statement would be the following:

<br>

### <strong>Students</strong>

|Student_ID   	| Name  	|  Address 	|  Age 	|   Phone_Number	|
|---	|---	|---	|---	|---	|
|  1 	| Frank  	| Perth  	| 25  	|  555555555 	| 
|  2 	| Jose  	| New York  	| 28  	|  666666666 	|
|  3 	| Sandra  	| Perth 	| 21  	|  888888888 	|
|  4 	| Dan 	| Boston 	| 32 	|  999999999 	|
|  5 	| Lisa	| Houston 	| 40 	|  333333333 	|

<br>

<strong>Removing Data:</strong>

The DELETE statement is used to remove a row from a table within a relational database. A WHERE clause is used to specify which row will be deleted.  If the WHERE clause is not included, all of the rows will be deleted from the table. The syntax used to achieve this is as follows: 

    DELETE [FROM] table [WHERE condition];

If we want to delete the row that we added previously with the INSERT statement, we would use the following statement:

    DELETE FROM Students WHERE Name='Lisa';

The outcome of the previous statement would be the following:

<br>

### <strong>Students</strong>

|Student_ID   	| Name  	|  Address 	|  Age 	|   Phone_Number	|
|---	|---	|---	|---	|---	|
|  1 	| Frank  	| Perth  	| 25  	|  555555555 	| 
|  2 	| Jose  	| New York  	| 28  	|  666666666 	|
|  3 	| Sandra  	| Perth 	| 21  	|  888888888 	|
|  4 	| Dan 	| Boston 	| 32 	|  999999999 	|

<br>
<br>

<strong>Changing Data:</strong>

The UPDATE statement is used to modify data within a table. Within the UPDATE statement, a SET clause is used to indicate the attribute that needs to be updated along with its value.  After the SET clause, a WHERE clause is used to specify the record that will be deleted.  If a WHERE clause is omitted, all of the records will be updated. The syntax used to achieve this is as follows: 

    UPDATE TableName
    SET Column1 = value1
    WHERE condition;

If we wanted to change the name of Frank to Franklin and update his address to Sydney (previous table), we would use the following statement:

    UPDATE Students
    SET Name = 'Franklin', Address= 'Sydney'
    WHERE Student_ID = 1;

The outcome of the previous statement would be the following:

### <strong>Students</strong>

|Student_ID   	| Name  	|  Address 	|  Age 	|   Phone_Number	|
|---	|---	|---	|---	|---	|
|  1 	| Franklin  	| Sydney  	| 25  	|  555555555 	| 
|  2 	| Jose  	| New York  	| 28  	|  666666666 	|
|  3 	| Sandra  	| Perth 	| 21  	|  888888888 	|
|  4 	| Dan 	| Boston 	| 32 	|  999999999 	|
<br>

<strong>Retrieving Data:</strong>

The SELECT statement is used to retrieve data from a table within a database.  A FROM clause is used to specify which table the data will be retrieved from.  Following a FROM clause is a WHERE clause, which specifies the row. A SELECT statement can be used to retrieve specific columns of data as well as all of the columns. The syntax used to achieve this is as follows: 

    SELECT Column1
    FROM TableName;

If we wanted to retrieve all of the data regarding Sandra in previous table, we would use the following statement:

    SELECT *
    FROM Students;
    Where Name= 'Sandra';

The outcome of the previous statement would be the following:

|Student_ID   	| Name  	|  Address 	|  Age 	|   Phone_Number	|
|---	|---	|---	|---	|---	|
|  3 	| Sandra  	| Perth 	| 21  	|  888888888 	|

<br>
<br>

## Question 12: Conduct research into a web application (app) and answer the following parts:  
 
 ### A. List and describe the software used by the app.


<strong>Application and Data:</strong>

- JavaScript - A programming language that can be used both client side and server side. 
- Python - An interpreted, object oriented programming language.
- React - A JavaScript framework for creating interactive UIs.
- Apache HTTP Server - an open source web server that assists in delivering web content over the internet.
- Amazon Web Services - A cloud computing platform that offers a large variety of infrastructure, platform and packaged software services.
- Google Cloud - A suite of cloud computer services including computing, data storage, and machine learning.
- PHP - An open source server-side scripting language. 

<strong>DevOps</strong>
- Jenkins - An open source automation server. 
- RequireJS - Manages dependencies between JS files.
- StatsD - A set of tools used for sending and collecting custom metrics from applications.

<br>

### B. Describe the hardware used to host the app

Up until completing its merge in 2020, Etsy ran on its own hardware infrastructure.  In that year they shifted from their nearly 2,000 on premises servers to using Google Cloud services.  Etsy utilizes Google Cloud's computing power and machine learning capabilities to host nearly 65 million items listed by etsy sellers. Google Cloud offers a combination of physical hardware and virtual machines to its Google Cloud customers. 
   
<br>

### C. Describe the interaction of technologies within the app

Etsy utilizes quite a variety of languages and tech to create their web app.  The back-end is composed of Backbone, PHP, and  the JavaScript based framework JQuery, which is used for its event handling. For their servers, Etsy utilizes Apache, Nginix, as well as various Google Cloud Services and Amazon Web Services.  For the front-end, Etsy uses a mix of technologies.  For some client-side management, Etsy uses WordPress which integrates well with the PHP back-end.  However, most of the front-end is created with the React framework paired with  HTML and CSS.


<br>

### D. Describe the way data is structured within the app

Structure of Data in the Database:

Etsy uses a relational database stored on Google Cloud Services. for the operation of their business. Etsy shifted to using MySQL from PostGres early on and has remained using it since.   


Structure of Product Information and Categories:

The Etsy app makes extensive use of taxonomies and stores their structured data within JSON files. The data at Etsy largely consists of product listings that are structured based on where they believe they belong in the marketplace. Etsy's taxonomy is a collection of hierarchies.  These hierarchies are composed of countless categories such as sweaters(6000+), attributes such as size (400+), values (3500+), and scales (90+). The JSON files represent the taxonomy.  Each category has a file which contains information about the relative placing of the category in the hierarchy, as well as scales for items in the specific categories. 


<br>


### E. Identify entities which must be tracked by the app 
  
There are countless entities that are tracked by Etsy, but at a basic level, entities that must be tracked are:
- buyer information (name, email, location, age, phone number)
- seller information (name, email, location, age phone number) 
- product listing (product name, description, price, location) 
- payment information(card number card expiry, card CVV, card type)
- reviews(score, description) 
- shipping information(address, phone number, email).  

<br>

### F . Identify the relationships and associations between the entities you have identified in part (e)

The relationships between the previously mentioned entities revolves around the listings, buyer information, and seller information.  Buyer information has relationships with Payment Information, Shipping Information, and Seller reviews.  The primary key (customer_id) of Buyer Information is a featured key in each of those (one to many).  Seller information has relationships with Product Listings and Seller Reviews.  The primary key (seller_ID) for Seller Information is a featured key in each of those (one to many). The Product Listings has a relationship with both shipping information and seller reviews. The primary key (product_ID) for Seller Reviews is featured in both of them (one to many).


<br>

### G . Design a schema using an Entity Relationship Diagram (ERD) appropriate for the database of this website (assuming a relational database model)
Link to GitHub if image fails to load: https://github.com/DTjomsland/T2A1-Workbook-A/blob/main/T2A1_Workbook_A.md

![](/images/dbrelation.PNG)
---


## Works Cited:

<br>

### Question 1

Cleveroad Inc. - Web and App development company. (n.d.). Web Application Architecture Fundamentals: What Types and Components Are There? [online] Available at: https://www.cleveroad.com/blog/web-application-architecture/.ClickIT. (2022).  [Accessed 11 Sep. 2022]
 
Web Application Architecture: The Latest Guide 2022. [online] Available at: https://www.clickittech.com/devops/web-application-architecture/. [Accessed 11 Sep. 2022]

<br>

### Question 2

The PostgreSQL Global Development Group (2019). PostgreSQL: The world’s most advanced open source database. [online] Postgresql.org. Available at: https://www.postgresql.org/.

Cybertec. (n.d.). Advantages of PostgreSQL - CYBERTEC | Data Science & PostgreSQL. [online] Available at: https://www.cybertec-postgresql.com/en/postgresql-overview/advantages-of-postgresql/. [Accessed 11 Sep. 2022]

<br>

### Question 3
APM (2016). Agile project management. [online] Apm.org.uk. Available at: https://www.apm.org.uk/resources/find-a-resource/agile-project-management/.

(Planio. (n.d.). The Ultimate Guide to Implementing Agile Project Management (and Scrum). [online] Available at: https://plan.io/blog/what-is-agile-project-management/#getting-started-with-agile-project-management-a-7-step-agile-implementation-plan-for-technical-teams. [Accessed 11 Sep. 2022]

<br>

### Question 4

Atlassian (2010). Git Workflow | Atlassian Git Tutorial. [online] Atlassian. Available at: https://www.atlassian.com/git/tutorials/comparing-workflows.

freeCodeCamp.org. (2021). How to Use Git and Git Workflows – a Practical Guide. [online] Available at: https://www.freecodecamp.org/news/practical-git-and-git-workflows/ [Accessed 11 Sep. 2022].

<br>

### Question 5

BrowserStack. (n.d.). Manual Testing for Beginners. [online] Available at: https://www.browserstack.com/guide/manual-testing-tutorial. [Accessed 11 Sep. 2022]

Guru99.com. (2019). Manual Testing Tutorial for Beginners: Concepts, Types, Tool. [online] Available at: https://www.guru99.com/manual-testing.html. [Accessed 11 Sep. 2022]

<br>

### Question 6

GeeksforGeeks. (2020). Principle of Information System Security. [online] Available at: https://www.geeksforgeeks.org/principle-of-information-system-security/. [Accessed 11 Sep. 2022]

<br>

### Question 7

Harrington, D. (2021). Data Security: Definition, Explanation and Guide. [online] www.varonis.com. Available at: https://www.varonis.com/blog/data-security. [Accessed 11 Sep. 2022]

www.ibm.com. (n.d.). What is encryption? Data encryption defined | IBM. [online] Available at: https://www.ibm.com/topics/encryption#:~:text=Data%20encryption%20is%20a%20way. [Accessed 11 Sep. 2022]

<br>

### Question 8

Duncan, B. (2020). Your Guide To The 13 Australian Privacy Principles. [online] Sprintlaw. Available at: https://sprintlaw.com.au/articles/13-australian-privacy-principles/ [Accessed 10 Sep. 2022]. [Accessed 11 Sep. 2022]

Office of the Australian Information Commissioner (2019). Read the Australian Privacy Principles. [online] OAIC. Available at: https://www.oaic.gov.au/privacy/australian-privacy-principles/read-the-australian-privacy-principles. [Accessed 11 Sep. 2022]

<br>

### Question 9

GeeksforGeeks. (2020). Difference between Primary Key and Foreign Key. [online] Available at: https://www.geeksforgeeks.org/difference-between-primary-key-and-foreign-key [Accessed 11 Sep. 2022]. [Accessed 11 Sep. 2022]

<br>

### Question 10
Pearlman, S. (2019). What is Data Integrity and Why Is It Important? - Talend. [online] Talend Real-Time Open Source Data Integration Software. Available at: https://www.talend.com/resources/what-is-data-integrity/. [Accessed 11 Sep. 2022]

Techopedia.com. (2019). What is Data Integrity in Databases? - Definition from Techopedia. [online] Available at: https://www.techopedia.com/definition/811/data-integrity-databases. [Accessed 11 Sep. 2022]

<br>

### Question 11

EDB. (n.d.). How to modify data in PostgreSQL using INSERT, UPDATE, UPDATE JOINS, DELETE and UPSERT. [online] Available at: https://www.enterprisedb.com/postgres-tutorials/how-modify-data-postgresql-using-insert-update-update-joins-delete-and-upsert. [Accessed 11 Sep. 2022]

GeeksforGeeks (2019). SQL | DDL, DQL, DML, DCL and TCL Commands - GeeksforGeeks. [online] GeeksforGeeks. Available at: https://www.geeksforgeeks.org/ [Accessed 11 Sep. 2022]

W3schools.com. (2019). SQL Tutorial. [online] Available at: https://www.w3schools.com/sql/. [Accessed 11 Sep. 2022]

<br>

### Question 12

Etsy. (1647). Etsy Engineering | Introduction to Structured Data at Etsy. [online] Available at: https://www.etsy.com/codeascraft/an-introduction-to-structured-data-at-etsy/.

InfoQ. (n.d.). An Introduction to Structured Data at Etsy. [online] Available at: https://www.infoq.com/news/2019/08/Introductio-Structured-Data-Etsy/. [Accessed 11 Sep. 2022]

Morgan, T.P. (2015). Etsy Shows How To Be Just Crafty Enough With Systems. [online] The Next Platform. Available at: https://www.nextplatform.com/2015/04/07/etsy-shows-how-to-be-just-crafty-enough-with-platforms/ [Accessed 11 Sep. 2022].

StackShare. (n.d.). Etsy - Etsy Tech Stack. [online] Available at: https://stackshare.io/etsy/etsy.

Steiner, I. (2017). Etsy Turns to Google to Host Its Infrastructure. [online] EcommerceBytes. Available at: https://www.ecommercebytes.com/2017/12/14/etsy-turns-google-host-infrastructure/ [Accessed 11 Sep. 2022].

wiredelta.com. (n.d.). How was Etsy Developed? - Wiredelta. [online] Available at: https://wiredelta.com/how-was-etsy-developed/. [Accessed 11 Sep. 2022]