# Venly Tech test

*Start of edit. Adding notes for future reference to this repository - dated 18/05/2023 at 21:47*

This project was completed for a tec exam that was carried out on Friday 12th of May 2023.

Criteria: Complete 9 tasks within a three hour time frame.

Solution: Each Push to this project is a timestamp with code that correlates to each task given.

*end of edit*

The project uses the following:
Java 17
Spring Boot 3 (Spring Web nad Spring Data JPA)
Maven
Docker (and Postgres)

Setup:
---
To install Postgres Docker Image: 
Type the following command from root directory in terminal 
> docker compose up -d

To Create Database from terminal:
From terminal type: 
> docker exec -it postgres bash

> psql -U jason

> CREATE DATABASE relation;

Result:
---
Failure

Feedback
---
- No DTO's
- Docker + postgres
- Native query to find by relation
- Lowercase and strip functionality in entity
- Validation in code

Positives about the test
---
You get to use the intellij IDE. It's not browser based.

Negatives
---
The test requrires access to your laptop camera.
Feedback was very crypic and took over two weeks.
So be prepared to sit there and concentrate ona timer for three hours.
Make minor mistakes like the ones in the feedback, and they will fail you.
I reached almost all the criteria, but it clearly made no difference.

Test Rating
---
3/10 : Unfair. Unrealistic. Intrusive.
Let's hope for a better chance in the future.
