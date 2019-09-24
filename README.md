# Introduction 
This repo is what you will use to submit your code for review. 
The goal is for you to push your code to this repository so we can review it. 
You may push code up here as early and often as you wish. The requirements for what you are to build are detailed below.
The only people who will access this are Lehigh County team members. In other words, no other Candidates will have access to this project. 

# Summary
You are to develop a web application that allows a user to enter expense information. Your application should meet the minimum requirements explained below and should follow the architecture guidelines outlined.

# Application Requirements
Your users are in need of a system where they can enter expense reports. Expense reports have a name (or purpose), and one or more line items. 

For example, if someone went to a training seminar on 2/1/2019, their expenses for this may resemble: 

*Note the format of this is for illustrative purposes only, the structure of the data is provided as a sample. 
#------------------------------------------- <br/>
Name: Training Seminar <br/>

Expenses: <br/>
Description: Flight <br/>
Amount: $200 <br/>
Payee: United <br/>
Date: 2/1/2019<br/>

Description: Seminar <br/>
Amount: $99 <br/>
Payee: Trainer's Inc. <br/>
Date: 2/3/2019<br/>
#-------------------------------------------

The basic flow for a user is to add a new Expense Report with a name. For that Expense Report, the user can add, edit or delete, expense line items.
Line items include description, amount, and the Payee. The user can also edit or delete the Expense Report. 

# Business Rules
Expense amounts must be greater than 0 <br/>
Description cannot be empty <br/>
Payee cannot be empty <br/>
Expense Report names must be unique <br/>

# Application Architecture 
The front end should be implemented as a web application. You are free to design the look and feel how you wish. 

Data should be retrieved from and saved in a database, such as a relational database system. 

# Source Code
All components, source code, tests, etc. should be pushed to this repo. You may also include any documentation you would wish. 
If you want to deploy a working version to a hosting environment for demonstration purposes, that is fine, but ALL SOURCE CODE must be in this Repo so we can review it.
Ideally, with minimal effort, we should be able to deploy and run the code ourselves. 

# Technology
There is no requirement to use a particular programming language or specific technology. Use whatever you feel you are best able to get the job done. 
Tip: See the job posting for the technology we primarily use. 

# Data
Data has been provided in the files Expenses.json. The data in Expenses.json should be converted into the database.
You supply the code and a general description of your data conversion approach, there is no need to develop a user interface to "load" the data on demand. 


# Development Process 
You may use this repo to create a GitHub Project and a Kanban board to create work items to document requirements, track your work, describe your approach, and report progress. 

# Evaluation
We will evaluate submissions based on the following areas:
- Requirements - Which functional requirements were met or not met? 
- Architecture - Which architectural requirements were met or not met? 
- Coding practices - What software engineering practices were employed? 
- Quality - How did you ensure the software behaved as expected? How was it tested? 
- Decision making - Ability to answer questions as to the decisions you made during your implementation. 
- Bonuses - Anything done beyond the minimum requirements
- NOTE: Implementing features not required (nice-to-have features) are unlikely to make up for missed requirements.
- Tip: Using the Project Kanban Board within this project to track your work and  communicate your understanding of the requirements is very good way to ensure you meet the requirements. 

# Communication
Please use GitHub Issues within this repo to communicate your questions, this helps us track conversations in orderly fashion and within context. Questions are encouraged, just use the Issues section of github to communicate them. 


# Timeframe
There is no deadline to complete this. 
However, only candidates that summit a project here will be considered for the next step. Candidates will be evaluated on a rolling basis. 

# Ready for review
When you are ready for us to review your submission, add an issue that reads "My code is ready for review!" 

