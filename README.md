# Introduction

Todoist is the productivity tool you need to get work and life organized. Collect tasks, organize projects, and plan your day, in this oportunity .
[![Todoist](https://get.todoist.help/hc/article_attachments/360011665940/Web___Inbox.png "Todoist")](https://get.todoist.help/hc/article_attachments/360011665940/Web___Inbox.png "Todoist")

## Goals
This repository has to goal, fulfill the next points:

- Get your authorization token and save it as an environment variable
- Create a new folder inside your collection for projects and another one for tasks.
- Create the following endpoints and its corresponding Tests: status codes, content, response time

## Installation:
what will you need to run this repository:

- Download [Postman](https://www.getpostman.com/ "Postman")
- Download [Nodejs]( https://nodejs.org/en/ "Nodejs")
- Download [newman ](https://www.npmjs.com/package/newman "newman ")
- Download [Visual Studio Code](https://code.visualstudio.com "Visual Studio Code") 
- npm install

Clone the repo into your local machine:
`https://github.com/Karenco1014/Todoist.git`
-  cd FQA_Challenge_backend
- Run test: npm run test



#HTTP Verbs

| HTTP METHOD  | POST  |GET   | PUT  |DELETE
| ------------ | ------------ | ------------ | ------------ |
| CRUD OP  | CREATE   | READ  | UPDATE  |DELETE
|  /tasks |  Create new tasks |  List tasks |  Bulk update |Delete all tasks
| /tasks/1234  |  Error |  Show task1 | If exists, update task1; If not, error   |Delete task1



