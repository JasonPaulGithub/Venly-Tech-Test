# ideal-octo-enigma

* Start of edit. Adding notes for future reference to this repository - dated 18/05/2023 at 21:47*

This project was completed for a tec exam that was carried out on Friday 12th of May 2023.

Criteria: Complete 9 tasks within a three hour time frame.

Solution: Each Push to this project is a timestamp with code that correlates to each task given.

* end of edit*

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
