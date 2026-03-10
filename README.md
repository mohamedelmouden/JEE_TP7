Student Management — Spring Boot :
---
Application REST de gestion des étudiants développée avec Spring Boot, JPA et documentée avec Swagge et postman.



Technologies utilisées :


- Java 17+

- Spring Boot

- Spring Data JPA

- MySQL (base de données)

- Swagger / springdoc-openapi (documentation API)

- JUnit 5 + Mockito (tests unitaires)

Configuration
----
propertiesspring.datasource.url=jdbc:mysql://localhost:3306/student_db

spring.datasource.username=root

spring.datasource.password=

spring.jpa.hibernate.ddl-auto=update

server.port=8081


Documentation Swagger :
---
Une fois l'application lancée, accéder à l'interface Swagger :

http://localhost:8081/swagger-ui.html

Elle permet de visualiser et tester tous les endpoints directement depuis le navigateur.



Les tests couvrent :
---

Sauvegarde d'un étudiant

Suppression d'un étudiant

Récupération de tous les étudiants

Comptage des étudiants

Récupération par année



Architecture de projet : 
---

<img width="609" height="933" alt="image" src="https://github.com/user-attachments/assets/493fbaa0-83a6-456e-8d9a-74f240811a74" />


video demo : lancement de l'application + postman
---


https://github.com/user-attachments/assets/0c8fb52e-2d7c-4e76-bc88-b13e80e2c06d


video demo : postman( suite )
----



https://github.com/user-attachments/assets/39b6fa4c-ea64-45f0-821c-06d54d5e8400


video demo : Swegger 
----



https://github.com/user-attachments/assets/43391561-3f43-4757-944a-d7d2231856d0








