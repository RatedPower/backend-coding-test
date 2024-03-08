# Spring Boot to-do app challenge

With this challenge we want to see your skills and the quality of the code, we will take into account the use of SOLID principles. You can use all the tools and libraries you want!


## Required tools

1. [Java 21](https://www.azul.com/downloads/#zulu)
2. [MySQL](https://dev.mysql.com/downloads/mysql/)
3. [Gradle](https://gradle.org/)

## Objectives

##### Principal

Develop the necessary functionalities for the application to be able to perform the following requests:

- **GET** http request that returns a list of tasks stored in the database.
   - Order results by priority or creation date.
   - Filter results by priority and/or completion.
- **GET** http request that returns a specific task by their ID.
- **POST** http request that stores a new task in the database.
- **PUT** http request that updates a specific task by their ID.
- **DELETE** http request that deletes a task in the database.
- Create a new entity called *SubtaskEntity* that allows one task to have multiple subtasks.
