# Introduction 
This repo is what you will use to submit your code for review. 
The goal is for you to push your code to this repository so we can review it. 
You may push code up here as early and often as you wish. The requirements for what you are to build are detailed below.
The only people who will access this are Lehigh County team members. In other words, no other Candidates will have access to this project. 

# Summary
You are to develop a web API for expense report information. Your application should meet the minimum requirements explained below and should follow the architecture guidelines outlined.

# Application Requirements
Your users are in need of a system where they can enter expense reports. Expense reports have a name (or purpose), and one or more line items. 
For example, if someone went to a training seminar on 2/1/2019, their expenses for this may resemble: 

*Note the format of this is for illustrative purposes only, the structure of the data is provided as a sample. 
#------------------------------------------- <br/>
Name: Training Seminar <br/>
Date: 2/1/2019<br/>

Expenses: <br/>
Description: Flight <br/>
Amount: $200 <br/>
Payee: United <br/>

Description: Seminar <br/>
Amount: $99 <br/>
Payee: Trainer's Inc. <br/>
#-------------------------------------------

The Web API should support the basic Create, Read, Update, and Delete functions for both an Expense Report and its Line Items. These Web API methods should manipulate records in a database. 

The API should also enforce the following business rules: 

- You may not have two expense reports with the same name, the name must be unique. 
- Every Expense Report Line Item must have dollar amount > 0
- Every Expense Report Line Item must have a non-empty date, description, and payee

Two additional API methods are required. 
- GetPayeeExpenseTotal - A method that returns each Payee in the system and the total amount paid to that payee from all expense report line items
- GetTop10LineItems - Returns the top 10 line items in the database with the greatest amount. This should return the Expense Report Name, Line item description, amount, date, and payee.  

# Application Architecture 
All components, source code, etc. should be pushed to this repo. You may also include any documentation you would wish. 
If you want to deploy a working version to a hosting environment for demonstration purposes, that is fine, but ALL SOURCE CODE must be in this Repo so we can review it.
Ideally, with mimimal effort, we should be able to deploy and run the code ourselves. 

# Technology
There is no requirement to use a particular programming language. Use whatever you feel you are best able to get the job done. 
Tip: See the job posting for the technology we primarily use. 

# Data
Data has been provided in the file Expenses.json. This data should be converted into your service's database.

# Development Process 
You may use this repo to create a project and a Kanban board to create work items (User Stories, tasks, etc.) to document requirements, track your work, describe your approach, and report progress. 

# Evaluation
We will evaluate submissions based on the following areas:
- Requirements - Which functional requirements were met or not met? 
- Architecture - Which architectural requirements were met or not met? 
- Coding practices - What software engineering practices were employed? 
- Quality - How did you ensure the software behaved as expected? 
- Decision making - Ability to answer questions as to the decisions you made during your implementation. 
- Bonuses - Anything done beyond the minimum requirements
- NOTE: Implementing features not required (nice-to-have features) are unlikely to make up for missed requirements. 
- Tip: Using the Kanban Board within this project to express Work Items (User Stories, tasks, etc.) that communicate your understanding of the requirements is very good way to ensure you meet them all. 

# Communication
Please use the Github Issues to communicate your questions, this helps us track conversations in an orderly fashion and within context. If you have a question, create a new issue and we will respond accordingly. 

Note: Your questions should be more around *what* and less around *how*. The *how* is for you to figure out. *What* is for when you need clarification on a requirement or guideline.

# Timeframe
There is no deadline to complete this. 
However, only candidates that summit a project here will be considered for the next step. Candidates will be evaluated on a rolling basis. 

# Ready for review
When you are ready for us to review your submission, add an issue that reads "My code is ready for review!" 

