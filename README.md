# Spring Boot to-do app challenge

With this challenge we want to see your skills and the quality of the code, we will take into account the use of SOLID principles. You can use all the tools and libraries you want!


## Required tools

1. [Java 11](https://adoptopenjdk.net/)
2. [MySQL](https://dev.mysql.com/downloads/mysql/)

## Objectives

##### Principal

Develop the necessary functionalities for the application to be able to perform the following requests:

- **GET** http request that returns a list of all tasks stored in the database.
- **GET** http request that returns a specific task by their ID.
- **POST** http request that stores a new task in the database.
- **PUT** http request that updates a specific task by their ID.
- **DELETE** http request that deletes a task in the database.

##### Optional

1. Improve the request that returns a list of tasks by adding the possibility to order and filter the results, for example:

    - Order results by priority or creation date.
    - Filter results by priority and/or completion.
    
2. Create a new entity called *SubtaskEntity* that allows one task to have multiple subtasks.
