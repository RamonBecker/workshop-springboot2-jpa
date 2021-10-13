# Workshop Java SpringBoot
 
## :information_source: Information 

The project had as its theme a basic sales workshop system that was developed during the Java programming course by professor Nelio Alves. During development, the following technologies were used: Hibernat, Spring Boot, H2 Database, etc. Only the BackEnd part of the project was carried out. Next, I will show the modeling that was carried out for the development of the system – class diagram – and also how to register and test the system.
## ⚠️ Prerequisite
[![Java Badge](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)](https://www.oracle.com/br/java/technologies/javase-downloads.html) >= 8 

![Spring Badge](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)

![JSON Badge](https://img.shields.io/badge/json-5E5C5C?style=for-the-badge&logo=json&logoColor=white)

![h2-logo-2 (1)](https://user-images.githubusercontent.com/44611131/136869740-c514d30e-d529-4167-a459-4fcd647cce19.png)


![JPA-hibernate (1)](https://user-images.githubusercontent.com/44611131/136869865-0e3d7476-5128-4471-8817-8df40315b970.jpg)

![Postman Badge](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white) OR ![Insomnia Badge](https://img.shields.io/badge/Insomnia-5849be?style=for-the-badge&logo=Insomnia&logoColor=white)

## 📌 Class Diagram

![diagrama de classe](https://user-images.githubusercontent.com/44611131/136870003-58a93012-4e1a-4c4d-b6f7-30f1ccb35222.PNG)


##  🔧 Install 


![](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)


```
https://github.com/RamonBecker/workshop-springboot2-jpa.git
```

![](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
```
git clone https://github.com/RamonBecker/workshop-springboot2-jpa.git
or install github https://desktop.github.com/ 
```

## ⚙️ Testing the project


To test the project you will need to clone the repository on your machine. You can choose both tools: postman or insomnia.
```
To download postman go to the following link: https://www.postman.com/downloads/
```
```
To download insomnia rentre from the following link: https://insomnia.rest/download
```
Remembering that you must choose the operating system corresponding to your machine.
After you have made your registration in these tools, run them and you must type the following in the address: 
```
http://localhost:8080/users/ 
```
according to the image below, to perform, for example, the GET operation, to search for all users in the database.


The following HTPP methods were implemented: PUT, DELETE, GET and POST.

The example was performed using Postman.

![tutorialPostman](https://user-images.githubusercontent.com/44611131/136871854-29ef6c37-1a01-49c9-a1b2-2c384490c41b.PNG)


## Accessing the H2 database


If you want to modify the user to access the database, modify the application.properties file.
Change the following:
```
spring.datasource.username=user
spring.datasource.password=password
```

Access in browser
```
http://localhost:8080/h2-console
```
If the JDBC URL is not configured, replace it with:
```
jdbc:h2:mem:testdb
```
## :zap: Technologies	

- Java
- JPA
- Hibernate
- Spring Boot
- H2 Database

## :memo: Developed features

- [x] CRUD User
- [x]  CRUD Product
- [x]  CRUD Category
- [x]  CRUD Order


## :technologist:	 Author

By Ramon Becker 👋🏽 Get in touch!



[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40'>](https://github.com/RamonBecker)  [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg' alt='linkedin' height='40'>](https://www.linkedin.com/in/https://www.linkedin.com/in/ramon-becker-da-silva-96b81b141//)
![Gmail Badge](https://img.shields.io/badge/-ramonbecker68@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:ramonbecker68@gmail.com)
