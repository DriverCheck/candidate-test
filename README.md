# DriverCheck - New Hire Test

> Complete as many of the tasks listed below in the time frame specified. 
#####  You do not need to complete all the tasks to be successful. Here is is what we're looking for (in this order):

    1) Does the app run? 
    2) Is it buggy?
    3) Ability to solve problems
    4) Design decisions 
    5) Ability to put together the full stack for a simple application 
    6) Code clarity and documentation
 
### Technologies

Submit your source project using the following technologies:

 - AngularJS
 - Bootstrap or Material Design
 - MongoDB
 - Node.js or Java (Tomcat)

### Source Control

Fork this repository and add your code and any assets we would require to take a look at your work. Structure your project as follows:

```
    root folder
        front-end -> AngularJS code
        back-end -> Node.js or Java code
        data -> mongodump of your testing database
```

### Project Overview

Create a responsive application (mobile first) to manage a list of companies, their employees and test results. Requirements:

  - Authentication is required (please provide us with a user and password)
  - Test results should be displayed as a simple "pass" or "fail"
  - A company can have many employees and an employee can have many tests
  - Must be able to read/add/edit/delete companies, employees and tests

#### Tasks

> Remember, do as many as you can, but you don't need to complete them all

* Create a database structure to store companies, employees and tests. 
    * *Keep in mind that you will need to query to see employees per company and tests per employee*
* Create web services in Node.js or Java that return data in json format to support CRUD operations for companies, employees and tests
* Create a single page client application in AngularJS to consume the web services above
    * Clients screen
        * List clients
        * Button to delete a client
        * New client form
        * Client details screen
    *  Employees screen
        *  List employees inside the Client details screen
        *  Button to delete an employee
        *  New employee form
        *  Employee details screen
    * Tests Results screen
        * List of tests inside the Employee details screen
        * Button to delete a test
        * New Test Result form
*  Add an option to search employees by name
*  Add an option to calculate the "pass" rate per client (% of passed tests)
*  Add a creation date to tests (calculated automatically)
*  Sort tests by newest/oldest
*  Filter global tests by date range


### Other pointers

* Focus first on making sure what you've build works well before adding more features
* Add whatever fields you consider necessary to the companies, employees and test collections so long as you can accomplish the above
* This list of tasks is meant to be too long! Don't feel overwhelemed by it. Focus first only in having a simple client and server that can communicate via the json services.
* Focus first on a mobile client, don't worry too much if it doesn't look great in large screens
* Commit as often as you can, we want to see how you progress. Don't do a massive commit at the end
* Include an explanation with your project if you feel is necessary

# Good luck!

If you have any questions please email `oros@drivercheck.ca`






