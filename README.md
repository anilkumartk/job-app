📌 JobApp – Spring Boot Job Application Portal

A simple Job Application Management Web App built using Spring Boot, JSP, Tomcat, and Bootstrap.
Users can view all jobs, add new jobs, and navigate using a clean Bootstrap UI.

🚀 Features

🏠 Home page with navigation (JSP-based UI)

📋 View all jobs

➕ Add a new job

🎨 Clean Bootstrap 5 UI

⚙️ MVC architecture (Controller → Service → Repository)

🔧 Hot reload with Spring Boot DevTools

🧪 JUnit testing support

🛠️ Tech Stack
Layer	Technology
Backend	Java , Spring Boot
Frontend	JSP, HTML, CSS, Bootstrap
Server	Embedded Tomcat
Build Tool	Maven
Templates	JSP + JSTL
Dev Tools	Spring Boot DevTools
📁 Project Structure
JobApp/
 ├── src/main/java/com/telusko/JobApp/
 │     ├── controller/   # Controllers (Home, Jobs)
 │     ├── service/      # Business logic
 │     ├── repository/   # Repositories
 │     └── JobAppApplication.java
 │
 ├── src/main/webapp/
 │     └── WEB-INF/views/
 │            ├── home.jsp
 │            ├── viewalljobs.jsp
 │            └── addjob.jsp
 │
 ├── src/main/resources/
 │     ├── application.properties
 │     └── static/     # CSS, JS
 │
 ├── pom.xml
 └── README.md

⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/anilkumartk/job-app.git
cd JobApp

2. Build the project
mvn clean install

3. Run the application
mvn spring-boot:run

🌐 Run the Application

Once the server starts, open in browser:

http://localhost:8080/

🔧 Configuration
application.properties



📦 Dependencies

Key dependencies from pom.xml:

spring-boot-starter-web

tomcat-jasper (JSP rendering) 

pom

jakarta.servlet.jsp.jstl-api

jakarta.servlet.jsp.jstl

spring-boot-devtools

lombok

spring-boot-starter-test

🤝 Contributing

Feel free to fork the repo and submit pull requests.
