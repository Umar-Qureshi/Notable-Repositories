### Notable Repositories

This repository showcases my contributions to group repositories and highlights what relevant skills I demonstrated in those projects.

1. [Transit.io - Distributed Transit Payment System](#1-transitio---distributed-transit-payment-system)
2. [Github Stats](#2-github-stats)
3. [BetterLearn - Cloud Based Collaborative Learning Platform (Google OAuth)](#3-betterlearn---cloud-based-collaborative-learning-platform)


# 1. Transit.io - Distributed Transit Payment System

Original Repo link: https://github.com/jleibovitch/distributed-systems-final

Link to the Report: https://docs.google.com/document/d/1t3wylBagI0dC_3NxD9Jm4UJ-dY3s_oQ9ynmPGFEy3e0/edit?usp=sharing

Link to code I have contributed (webserver): https://github.com/jleibovitch/distributed-systems-final/tree/main/web_server/server

### Relevant skills I demonstrated in this project:

- Ability to use Python Flask in a variety of ways including Flask-Login, Flask-WTF (forms) and Flask-Bcrypt (Hashing)
- Creating a Database and table using SQL Alchemy and integrating it with Flask
- Receive incoming requests from an external api to store and update information within user tables

### Brief Summary:
This project is a distributed account-based transit payment system that intends to allow users to pay for transit fares via a card tap or using the NFC feature on smartphones. We utilize a multi-layered architecture with a centralized server, creating a distributed system that serves users from multiple locations and stations. (More details in the report)

### Screenshots of Webserver:
![TransitIO_Screenshots](https://user-images.githubusercontent.com/22453457/127223377-56869f61-357c-4e1c-97c1-3a1f8cfe6896.png)

### Snippets of Notable code I contributed:

Form Validation with Flask (found in forms.py):

![forms](https://user-images.githubusercontent.com/22453457/127225475-12ad4c2b-9c35-4175-964b-d4e4e6470fd2.png)

Table Creation with SQL Alchemy (found in models.py):

![tables](https://user-images.githubusercontent.com/22453457/127226213-9d4ea662-55c7-4c1f-b3be-78c3da5f77e1.png)

Using Flask to log a user in (found in routes.py):

![image](https://user-images.githubusercontent.com/22453457/127226819-363be8e8-fe88-40ce-a3de-b598d3c17be2.png)

Handling incoming transactions from the Train Station (found in web_api.py): 

![image](https://user-images.githubusercontent.com/22453457/127227327-fc58dbc0-f090-4b07-ae5e-fafbb8ce6772.png)


---
---

# 2. Github Stats

Original Repo link: https://github.com/a-saf/SOFE3700-GitHubStats

Link to the Report: https://github.com/a-saf/SOFE3700-GitHubStats/blob/master/phase%203%20-%20report%20.pdf


### Relevant skills I demonstrated in this project:

- Used MySQL Workbench to create a database and tables from scratch
- Pppulated the database and tables with real data from the Gitub API
- Connected the Database to our web application with XAMPP and PHP
- Created 10 Distinct Views including complex views such as various types of Joins & Nested Queries
- Used Javascript to create visual charts

### Brief Summary:

Github provides some general statistics on individual repository pages but currently there is no convenient way to look at real-time commit statistics across repositories of different users at a glance. The goal of this project is to create a simple database web application that will query, store, analyze and render current GitHub commit statistics using GitHub public REST API. The application will focus on sorting and pulling commit statistics from public repositories of users located in Ontario, Canada. This data will be analyzed for the following metrics: which months and days of the week and hours of the day have the most commits, most commonly used programming languages, and the categories of software products these commits represent.

### Screenshots:

![image](https://user-images.githubusercontent.com/22453457/133914482-3a790e7c-aa0e-464c-b96b-6800276a6bb2.png)
![image](https://user-images.githubusercontent.com/22453457/133914498-fe2d9aa9-5e44-4b6a-96d8-ae0272c6e795.png)
![image](https://user-images.githubusercontent.com/22453457/133914516-a2a641ed-7126-4e56-b0c6-337b3cdfd635.png)
![image](https://user-images.githubusercontent.com/22453457/133914542-685ef393-264a-42bd-86a4-b5b7cb907639.png)


---
---

# 3. BetterLearn - Cloud Based Collaborative Learning Platform

Original Repo link: https://github.com/GabrielGelgor/BetterLearn/tree/master/Services

Link to the Report: https://docs.google.com/document/d/1986_lgnWJtDS1-YcSnF-ZhCwd_iF8FaIR-U-u3hIUNk/edit?usp=sharing

Link to code I have contributed (Authentication): https://github.com/GabrielGelgor/BetterLearn/tree/master/Services/Authentication

### Relevant skills I demonstrated in this project:

- Implementing Google Oauth2 with cookies using gmail, so users can create an account or login with ease
- Collaborated with my team so the Authentication microservice worked with the DBHelper microservice in a cloud/Kubernetes environment
- Ensured the cookies are encrypted and can communicate with Google strategy to ensure secure login
- When logged in user information can be retrieved from the Database using the secure cookie

### Brief Summary:
Better Learn is a collaborative development platform for students, by students. Users can create a profile detailing information about their areas of interest, what technologies they’re familiar with, and optionally a link to a portfolio. Next, they can either join or create their own project.

Since BetterLearn will ideally be utilized by a large number of clients, scalability, modularity, and maintainability were at the forefront of our minds while designing. Adopting a micro service oriented approach, we will be capitalizing on cloud technology solutions like Docker and Kubernetes during development to achieve our desired outcome.

### Screenshots:
![image](https://user-images.githubusercontent.com/22453457/133939549-ef205d7a-d47b-4e72-b434-6f474083c43b.png)


### Snippets of Notable code I contributed:
(Found in Authentication/services/passport.js)

Creating the cookie:

![image](https://user-images.githubusercontent.com/22453457/133940378-27df559d-8154-446e-a11e-57daffb7de4c.png)


Checking if user exists, if not a new user is created:

![image](https://user-images.githubusercontent.com/22453457/133939921-ebfa62ae-fc21-4089-a7e0-befe41aed3e4.png)


### Snippets of Googles OAuth Architecture:

Source: 5. S. Grider, “StephenGrider/FullstackReactCode,” GitHub. [Online]. Available: https://github.com/StephenGrider/FullstackReactCode/tree/master/diagrams/04. [Accessed: 04-Apr-2021]. 

![image](https://user-images.githubusercontent.com/22453457/133940608-3619d548-5419-4a37-8a41-019c2d979335.png)

![image](https://user-images.githubusercontent.com/22453457/133940781-12af3c11-a27c-4a25-b47f-3439a5df617b.png)


### Snippet I wrote in the report about Google OAuth:

![image](https://user-images.githubusercontent.com/22453457/133940971-64221962-128b-4889-9651-5b7ad51a6936.png)



