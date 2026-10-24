# Student Management System (5-Page Spring Boot Website)

**Assignment:** Class Work – Assignment - 1  
**Technologies:** Java 17+, Spring Boot 3.2.x, Spring Web, HTML5, CSS3  

---

## 📌 Project Overview
A clean, responsive 5-page web application built with **Spring Boot** and **Spring Web**. Static web pages are served directly out of `src/main/resources/static/` using Spring Boot's built-in static resource handling—no Thymeleaf, database, or JPA dependencies required.

---

## 📂 Project Structure
```text
spring-boot-web-project/
├── pom.xml
├── README.md
└── src/
    └── main/
        ├── java/
        │   └── com/
        │       └── example/
        │           └── SpringBootWebApplication.java
        └── resources/
            ├── application.properties
            └── static/
                ├── css/
                │   └── style.css
                ├── index.html
                ├── about.html
                ├── product.html
                ├── features.html
                └── contact.html
```

---

## 🌐 Page URLs & Details

| # | Page Name | File Path | URL | Description |
|---|---|---|---|---|
| 1 | **Home Page** | `static/index.html` | [http://localhost:8080/](http://localhost:8080/) | Project title, welcome message, overview cards, and navigation menu |
| 2 | **Project Creator** | `static/about.html` | [http://localhost:8080/about.html](http://localhost:8080/about.html) | Information about student creator (Rahul Kumar, B.Tech CS, skills, intro) |
| 3 | **Product Page** | `static/product.html` | [http://localhost:8080/product.html](http://localhost:8080/product.html) | Product name, description, purpose, technologies, target users |
| 4 | **Features Page** | `static/features.html` | [http://localhost:8080/features.html](http://localhost:8080/features.html) | 6 core features: Add, View, Update, Delete, Search, and Reports |
| 5 | **Contact Page** | `static/contact.html` | [http://localhost:8080/contact.html](http://localhost:8080/contact.html) | Creator contact info (Email, Phone, College, Location) & inquiry form |

---

## 🚀 How to Run the Application

### Option 1: Terminal / Command Line
1. Navigate to the project root directory:
   ```bash
   cd spring-boot-web-project
   ```
2. Run using Maven:
   ```bash
   mvn spring-boot:run
   ```
3. Open your browser and navigate to:
   [http://localhost:8080](http://localhost:8080)

### Option 2: IntelliJ IDEA / Eclipse / VS Code
1. Open or import the `spring-boot-web-project` folder as a Maven project.
2. Locate `src/main/java/com/example/SpringBootWebApplication.java`.
3. Right-click and choose **Run 'SpringBootWebApplication'**.
4. Open [http://localhost:8080](http://localhost:8080) in your web browser.
