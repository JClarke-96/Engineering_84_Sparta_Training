# Week 1 Business Week
## Inteview questions and answers
### Questions
#### What is DevOps and what is the benefit of it?
DevOps is a set of practices combining software development and IT operations designed to shorten the systems development life cycle by reducing time taken for communication between different teams.
- Ease of use
- Flexibility
- Robustness
- Cost

#### Why do you want to work for Sparta Global?
Sparta provides comprehensive training for DevOps and many other areas, working with Sparta will allow me to upskill before working with a client to obtain crucial experience for a career.

#### Where do you see yourself in 2-5 years time?
In 2-5 years time I'd like to be working in DevOps role, having completed my training and 2 years as a Junior DevOps Consultant before moving to work for a client directly.

#### What is Agile and what is the benefit of implementing it?
Agile is a style of software development focused on iterative development where requirements and solutions evolve over the course of a project, allowing far greater flexibility and software to be produced in increments with continuous delivery.
- Individuals and Interactions over Processes and Tools.
- Working Software over Comprehensive Documentation.
- Customer Collaboration over Contract Negotiation.
- Responding to Change over Following a Plan.

#### What is SCRUM and what is the benefit of implementing it?
SCRUM is an agile framework that emphasises teamwork and accountability with daily standups and retrospectives to highlight any issues or improvements that can be made.

# Week 2 SQL
## Theory
### Join
A JOIN combines rows from two or more tables based on a related column shared between tables. For example, a store that has customers with membership may have a database of customers, and a database of customer trends. These databases will share a Customer ID which is used to connect the two.

#### Types of Join
<strong>INNER JOIN</strong> - Returns records that have values in both tables.

<strong>LEFT JOIN</strong> - Returns all records in the left table, with matched records from the right table.

<strong>RIGHT JOIN</strong> - Returns all records in the right table, with matched records from the left table.

<strong>OUTER JOIN</strong> - Returns all records with a match in either the left or right tables.

### SQL Keys
Keys in SQL are used to fetch records and create relationships using different types of JOIN.

#### Types of Key
<strong>Primary Key</strong> - Used to uniquely identify a record in a database table. It cannot contain null or duplicate values.

<strong>Foreign Key</strong> - Is a Primary Key in a different table and can contain null or duplicate values.

<strong>Composite Key</strong> - Combination of more than one field or column and can be used as a Primary Key.

### DML / DDL
#### DDL (Data Definition Language)
Deals with database layout, descriptions, and how data should reside in the database.<br>
Commands include: CREATE, ALTER, DROP, TRUNCATE, COMMENT, & RENAME.

#### DML (Data Manipulation Language)
Deals with data manipulation to store, modify, retrieve, delete, and update data in a database.<br>
Commands include: SELECT, INSERT, UPDATE, DELETE, MERGE, CALL, EXPLAIN PLAN, & LOCK TABLE.

### Normalisation
#### 1st Normal Form
- Each table cell contains a single value.
- Each record needs to be unique.<br>

#### 2nd Normal Form
- Single column Primary Key.
- Meets conditions from 1st Normal Form.<br>

#### 3rd Normal Form
- Has no transitive functional dependencies.
- Meets conditions from 2nd Normal Form.<br>

### Entity Relationship Diagram
An entity relationship diagram shows data structures within databases. These diagram show each table and the fields within them, highlighting Primary and Foreign Keys as well as showing the relationships they form between tables. These relationships can be in three different types.

<strong>One to One</strong> - Each value for a table links to only one value in another.<br>
Example: A store has one manager, a manager only works at one store.
  
<strong>One to Many</strong> - Each value for a table can link to many values in another.<br>
Example: A store can have many employees, an employee can only work at one store.

<strong>Many to Many</strong> - Each value can have many values from either table.<br>
Example: A customer can shop at many stores, a store can have many customers.

## SQL notes
### Syntax
- SELECT
- DISTINCT
- FROM
- WHERE
- GROUP BY
- HAVING
- ORDER BY

# Week 3 Python
## What is Git & GitHub?
Git is used for version control of software, pushing projects to a repository where versions are stored as different iterations. GitHub is a website used to store and view repositories online.

## What is OOP?
### Benefits of OOP
Allows code to be reused meaning it doesn't have to be repeated in multiple locations, reduces data redundancy, and security with hiding information using abstraction.

### Four Pillars of OOP
- Inheritence (sharing of information)
- Encapsulation (grouping of information)
- Abstraction (hiding of information)
- Polymorphism (redefining of information)

## What is API?
Application Programming Interface is an interface that defines interactions between multiple software applications or mixed hardware-software intermediaries.

## What is PIP?
PIP is a package-management system for Python, used to install and manage software packages.

# Week 4 Python
## What is TDD?
Test Driven Development is used to test code before it is written. Tests are created that would be expected to pass after the code is complete, then the tests are ran and all fail as the code does not exist. Code is then written in order to make the tests pass, after they all pass you have an initial iteration of the working code.

### Why use TDD?
Test Driven Development reduces the number of bugs in production and improves code quality, making it easier to maintain and understand.

# Week 5 Plane Project
## What did we do?
### How did we use DRY?
### How did we use OOP?
### How did we use TDD?

# Week 6 Virtualisation


- MVC, MVT, DBS

# Week 7 AWS and Cloud Computing


