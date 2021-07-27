### Notable Repositories

This repository showcases my contributions to group repositories and highlights what relevant skills I demonstrated in those projects.

# Transit.io - Distributed Transit Payment System

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



