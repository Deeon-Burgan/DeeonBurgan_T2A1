# RfQ Response

## Q1. Describe the architecture of a typical Rails application.  
Rails typically uses an MVC architecture, which stands for, Model, View, Controller respectively.  

A brief explanation of each part of the architecture follows below:  
### Model:
The model is the storage of our data and logic.  
In Rails the model represents the information in the database as well as the logic behind any validation.  
### View:  
The view is what's sent back to the browser, the GUI.  
The view is the front-end of the application.  
In Rails the view contains html.erb files, where the embedded ruby is fairly simple, mainly used to display data from the model, or used to create fields to edit/add to the model. 
### Controller:  
The controller is what's needed to manage the view and model of our application.

## Q2. Identify a database management system commonly used in web applications and discuss the pros and cons of this database. 
### PostgreSQL:
"PostgreSQL is a powerful, open source object-relation database sytem that uses and extends the SQL language" - postgresql.org 
### Pros:
* *Extensibility:*  
PostgreSQL isn't a fixed database system, if you're in need of an additional feature in Postgres you can add it, which is relatively difficult with other database systems.

* *Security:*
Postgres has inbuilt features which relate to security, and it also has extensions available which you are able to use to enhance the security of your database.

### Cons:
* *Open source:*
Being an open source database application, PostgreSQL is not owned by a singular organisation. Given this fact, the system comes with no warranty and it has no liability.  

* *Slower performance:* 
PostgreSQL is known for having a number of issues with performance and backup recovery.  
PostgreSQL due to it's relational database structure, can struggle and perform slowly when working with a large number stores located in rows and columns of a table containing many fields of inforation

aalpha.net/blog/pros-and-cons-of-using-postgresql-for-application-development/

## Q3. Discuss the implementation of Agile project management methodology.  
I'm going to answer this question using my experience, having worked on a number of projects with a number of teams, working with Agile methodologies.  
The Agile methodology is an alternative project management system, that focuses on separating a project into small parts, which helps prioritize customer feedback in the development process.  
Once work begins on a project, teams will cycle through a process of planning, executing and evaluating each sprint, all while being in near constant contact with customer's to get their feedback to ensure requirements are being met.  
The Agile methodology is good because instead 'betting everything on a "big bang" launch', Agile allows a team to deliver their work in small, consumable increments which can be reviewed, and have feedback come in, regularly.

atlassian.com/agile  
wrike.com/project-management-guide/faq/what-is-agile-methodology-in-project-management/

## Q4. Provide an overview and description of a standard source control workflow.
### Feature branch workflow:
The feature branch workflow is a source control style which has the core idea that each feature being developed should take place on a dedicated branch, instead of being worked on the master branch.  
 Doing this makes it easy for a number of developers to work on a feature together without harming the main codebase, which also means the master branch will never be broken.

 Essentially the way this style would be implemented is as such:  
 1. A feature will be planned and discussed
 2. A new branch will be created for this feature, generally forking from the master branch
 3. Developers will work on this new branch at all times when working on the new feature
 4. When the feature has been completed and tested, it will be merged into the master branch

 atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow

 ## Q5. Provide an overview and description of a standard software testing process.
### Test driven development:
Test driven development is an approach in which test cases of a program are developed before the actual program is developed, to specify and validate what the code needs to and will do.  
TDD, starts with designing and developing test for every functionality of an application, then moves onto coding only if said test has failed, which avoids duplication of code.

