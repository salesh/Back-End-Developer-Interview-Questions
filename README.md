Back-End Developer Interview Questions
======================================

This page has been translated to [Chinese](https://github.com/monklof/Back-End-Developer-Interview-Questions) by [monklof](https://github.com/monklof).

I started writing down this list as a personal reminder of topics I had the chance to discuss with colleagues and friends, and that I wanted to deepen...

I'm not a big fan of asking technical questions in job interviews: I rather prefer to sit together with candidates in front of some real code, hands on the keyboard, facing a real problem, and have a full day of pair programming, hopefully rotating with all the other team members. Yet, I feel some technical questions could be a good starting point to begin an engaging and nice conversation, and this can be useful to get a deeper knowledge of each others.

This repo collects a number of back end related questions that can be used when vetting potential candidates. It is by no means recommended to use every single question on the same candidate: that would take hours, and would have no sense at all, as they cover a too broad set of topics for a single developer's to possibly know. Browse the section you find more relevant for your context, and pick the questions that give you more ideas on the conversation to have.

### Notice
Most of the questions are open-ended, and some of them just don't have a *right* or a *wrong* answer. On the contrary, they are intended to be used as the starting point for a conversation that hopefully tells you more about the person's capabilities than a straight answer would. Personally, I would even choose the questions whose answers are not yet clear to me.

Again, I stress that just asking questions is hardly sufficient. Complete the interview with a long pair programming session with your candidates: it is one of the best opportunities to know each others' style and approach and to let candidates know some details about their future day job.

This project is admittedly inspired by [Front-end Job Interview Questions](https://github.com/darcyclarke/Front-end-Developer-Interview-Questions) by [@darcyclarke](https://github.com/darcyclarke)



### Where are the answers?

Sooner or later I will complete it with the relative answers. Feel free to contribute, it would be highly appreciated!


## <a name='toc'>Table of Contents</a>

  1. [Questions about Design Patterns](#patterns)
  1. [Questions about Code Design](#design)
  1. [Questions about languages](#languages)
  1. [Web Questions](#web)
  1. [Databases Questions](#databases)
  1. [NoSQL Questions](#nosql)
  1. [Code Versioning Questions](#codeversioning)
  1. [Concurrency Questions](#concurrency)
  1. [Questions about Distributed Systems](#distributed)
  1. [Questions about Software Lifecycle and Team Management](#management)
  1. [Questions about logic and algorithms](#algorithms)
  1. [Questions about Software Architecture](#architecture)
  1. [Questions about Service Oriented Architecture and Microservices](#soa)
  1. [Questions about Security](#security)
  1. [General Questions](#general)
  1. [Open Questions](#open)
  1. [Questions based on snippets of code](#snippets)
  1. [Bill Gates Style Questions](#billgates)




### [[↑]](#toc) <a name='web'>Questions about Web development:</a>
* [COOK](http://www.eff.org) Why are first-party cookies and third-party cookies treated so differently?
* [APIV](http://www.eff.org) How would you manage Web Services API versioning?
* [SPA](http://www.eff.org) From a backend perspective, are there any disadvantages or drawbacks on the adoption of Single Page Applications?
* [STATELS](http://www.eff.org) Why do we usually put so much effort for having stateless services? What's so good in stateless code and why and when is statefulness bad?
* [RESTSOAP](http://www.eff.org) REST and SOAP: when would you choose one, and when the other?
* [MVC](http://www.eff.org) In web development, Model-View Controller and Model-View-View-Model approaches are very common, both in the backend and in the frontend. What are they, and why are they advisable?


### [[↑]](#toc) <a name='web'>Questions about Web development:</a>
* Why are first-party cookies and third-party cookies treated so differently? [COOK](http://www.eff.org)
* How would you manage Web Services API versioning? [APIV](http://www.eff.org)
* From a backend perspective, are there any disadvantages or drawbacks on the adoption of Single Page Applications? [SPA](http://www.eff.org)
* Why do we usually put so much effort for having stateless services? What's so good in stateless code and why and when is statefulness bad? [STATELS](http://www.eff.org)
* REST and SOAP: when would you choose one, and when the other? [RESTSOAP](http://www.eff.org)
* In web development, Model-View Controller and Model-View-View-Model approaches are very common, both in the backend and in the frontend. What are they, and why are they advisable? [MVC](http://www.eff.org)


### [[↑]](#toc) <a name='web'>Questions about Web development:</a>

|    |  |
|---|---|
| [COOK](http://www.eff.org)     | Why are first-party cookies and third-party cookies treated so differently?                                                                                                         |
| [APIV](http://www.eff.org)     | How would you manage Web Services API versioning?                                                                                                                                   |
| [SPA](http://www.eff.org)      | From a backend perspective, are there any disadvantages or drawbacks on the adoption of Single Page Applications?                                                                   |
| [STATELS](http://www.eff.org)  | Why do we usually put so much effort for having stateless services? What's so good in stateless code and why and when is statefulness bad?                                          |
| [RESTSOAP](http://www.eff.org) | REST and SOAP: when would you choose one, and when the other?                                                                                                                       |
| [MVC](http://www.eff.org)      | In web development, Model-View Controller and Model-View-View-Model approaches are very common, both in the backend and in the frontend. What are they, and why are they advisable? |


### [[↑]](#toc) <a name='web'>Questions about Web development:</a>

|                                                                                                                                                                                     |                                |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------|
| Why are first-party cookies and third-party cookies treated so differently?                                                                                                         | [COOK](http://www.eff.org)     |
| How would you manage Web Services API versioning?                                                                                                                                   | [APIV](http://www.eff.org)     |
| From a backend perspective, are there any disadvantages or drawbacks on the adoption of Single Page Applications?                                                                   | [SPA](http://www.eff.org)      |
| Why do we usually put so much effort for having stateless services? What's so good in stateless code and why and when is statefulness bad?                                          | [STATELS](http://www.eff.org)  |
| REST and SOAP: when would you choose one, and when the other?                                                                                                                       | [RESTSOAP](http://www.eff.org) |
| In web development, Model-View Controller and Model-View-View-Model approaches are very common, both in the backend and in the frontend. What are they, and why are they advisable? | [MVC](http://www.eff.org)      |



### [[↑]](#toc) <a name='web'>Questions about Web development:</a>
#### Migration
How would you migrate an application from a database to another, for example from MySQL to PostgreSQL? If you had to manage that project, which issues would you expect to face? [Answers](http://some.com]
#### Db and Null
Why do databases treat null as a so special case? For example, why does ```SELECT * FROM table WHERE field = null``` not match records with null ``field`` in SQL? [Answers](http://some.com)
#### ACID
ACID is an acronym that refers to Atomicity, Consistency, Isolation and Durability, 4 properties guaranteed by a database transaction in most database engines. What do you know about this topic? Would you like to elaborate? [Answers](http://some.com)
#### Migrations
How would you manage database schema migrations? That is, how would you automate changes to database schema, as the application evolves, version after version? [Answers](http://some.com)
#### Lazy loading
How is lazy loading achieved? When is it useful? What are its pitfalls? [Answers](http://some.com)
#### N+1 problem
The so called "N + 1 problem" is an issue that occurs when code needs to load the children of a parent-child relationship with a ORMs that have lazy-loading enabled, and that therefore issue a query for the parent record, and then one query for each child record. How to fix it?[Answers](http://some.com)
#### Expensive queries
How would you find the most expensive queries in an application? [Answers](http://some.com)
#### Db normalization
In your opinion, is it always needed to use database normalization? When is it advisable to use denormalized databases? [Answers](http://some.com)
#### Blue-Green Deployment
Of of the Continuous Integration's techniques is called Blue-Green Deployment: it consists in having two production environments, as identical as possible, and in performing the deployment in one of them while the other one is still operating, and than in safely switching the traffic to the second one after some convenient testing. This technique becomes more complicated when the deployment includes changes to the database structure or content. I'd like to discuss this topic with you. [Answers](http://some.com)



### [[↑]](#toc) <a name='web'>Questions about Web development:</a>
#### Migration | [Answers](http://some.com)
How would you migrate an application from a database to another, for example from MySQL to PostgreSQL? If you had to manage that project, which issues would you expect to face?

Or example, why does ```SELECT * FROM table WHERE field = null``` not match records with null ``field`` in SQL?

#### Db and Null
Why do databases treat null as a so special case? For example, why does ```SELECT * FROM table WHERE field = null``` not match records with null ``field`` in SQL? [Answers](http://some.com)
#### ACID
ACID is an acronym that refers to Atomicity, Consistency, Isolation and Durability, 4 properties guaranteed by a database transaction in most database engines. What do you know about this topic? Would you like to elaborate? <br/>[Answers](http://some.com)
#### Migrations
How would you manage database schema migrations? That is, how would you automate changes to database schema, as the application evolves, version after version? <br/>[Answers](http://some.com)
#### Lazy loading
How is lazy loading achieved? When is it useful? What are its pitfalls? <br/>[Answers](http://some.com)
#### N+1 problem
The so called "N + 1 problem" is an issue that occurs when code needs to load the children of a parent-child relationship with a ORMs that have lazy-loading enabled, and that therefore issue a query for the parent record, and then one query for each child record. How to fix it?<br/>[Answers](http://some.com)
#### Expensive queries
How would you find the most expensive queries in an application? <br/>[Answers](http://some.com)
#### Db normalization
In your opinion, is it always needed to use database normalization? When is it advisable to use denormalized databases? <br/>[Answers](http://some.com)
#### Blue-Green Deployment
Of of the Continuous Integration's techniques is called Blue-Green Deployment: it consists in having two production environments, as identical as possible, and in performing the deployment in one of them while the other one is still operating, and than in safely switching the traffic to the second one after some convenient testing. This technique becomes more complicated when the deployment includes changes to the database structure or content. I'd like to discuss this topic with you. <br/>[Answers](http://some.com)



### [[↑]](#toc) <a name='web'>Questions about Web development:</a>
#### [Migration](http://some.com)
How would you migrate an application from a database to another, for example from MySQL to PostgreSQL? If you had to manage that project, which issues would you expect to face?
#### [Db and Null](http://some.com)
Why do databases treat null as a so special case? For example, why does ```SELECT * FROM table WHERE field = null``` not match records with null ``field`` in SQL?
#### [ACID](http://some.com)
ACID is an acronym that refers to Atomicity, Consistency, Isolation and Durability, 4 properties guaranteed by a database transaction in most database engines. What do you know about this topic? Would you like to elaborate?
#### [Migrations](http://some.com)
How would you manage database schema migrations? That is, how would you automate changes to database schema, as the application evolves, version after version?
#### [Lazy loading](http://some.com)
How is lazy loading achieved? When is it useful? What are its pitfalls?
#### [N+1 problem](http://some.com)
The so called "N + 1 problem" is an issue that occurs when code needs to load the children of a parent-child relationship with a ORMs that have lazy-loading enabled, and that therefore issue a query for the parent record, and then one query for each child record. How to fix it?
#### [Expensive queries](http://some.com)
How would you find the most expensive queries in an application?
#### [Db normalization](http://some.com)
In your opinion, is it always needed to use database normalization? When is it advisable to use denormalized databases?
#### [Blue-Green Deployment](http://some.com)
Of of the Continuous Integration's techniques is called Blue-Green Deployment: it consists in having two production environments, as identical as possible, and in performing the deployment in one of them while the other one is still operating, and than in safely switching the traffic to the second one after some convenient testing. This technique becomes more complicated when the deployment includes changes to the database structure or content. I'd like to discuss this topic with you.





### [[↑]](#toc) <a name='web'>Questions about Web development:</a>
* Why are first-party cookies and third-party cookies treated so differently? [COOK](http://www.eff.org)
* How would you manage Web Services API versioning? [APIV](http://www.eff.org)
* From a backend perspective, are there any disadvantages or drawbacks on the adoption of Single Page Applications? [SPA](http://www.eff.org)
* Why do we usually put so much effort for having stateless services? What's so good in stateless code and why and when is statefulness bad? [STATELS](http://www.eff.org)
* REST and SOAP: when would you choose one, and when the other? [RESTSOAP](http://www.eff.org)
* In web development, Model-View Controller and Model-View-View-Model approaches are very common, both in the backend and in the frontend. What are they, and why are they advisable? [MVC](http://www.eff.org)


### [[↑]](#toc) <a name='web'>Questions about Web development:</a>
* Why are first-party cookies and third-party cookies treated so differently? [Answers](http://www.eff.org)
* How would you manage Web Services API versioning? [Answers](http://www.eff.org)
* From a backend perspective, are there any disadvantages or drawbacks on the adoption of Single Page Applications? [Answers](http://www.eff.org)
* Why do we usually put so much effort for having stateless services? What's so good in stateless code and why and when is statefulness bad? [Answers](http://www.eff.org)
* REST and SOAP: when would you choose one, and when the other? [Answers](http://www.eff.org)
* In web development, Model-View Controller and Model-View-View-Model approaches are very common, both in the backend and in the frontend. What are they, and why are they advisable? [Answers](http://www.eff.org)




### [[↑]](#toc) <a name='web'>Questions about Web development:</a>
* [+](http://www.eff.org) Why are first-party cookies and third-party cookies treated so differently?
* [+](http://www.eff.org) How would you manage Web Services API versioning?
* [+](http://www.eff.org) From a backend perspective, are there any disadvantages or drawbacks on the adoption of Single Page Applications?
* [+](http://www.eff.org) Why do we usually put so much effort for having stateless services? What's so good in stateless code and why and when is statefulness bad?
* [+](http://www.eff.org) REST and SOAP: when would you choose one, and when the other?
* [+](http://www.eff.org) In web development, Model-View Controller and Model-View-View-Model approaches are very common, both in the backend and in the frontend. What are they, and why are they advisable?

