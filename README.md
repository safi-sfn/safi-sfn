# Hi there, I'm Safiruddin 👋

## 🚀 Backend Specialist
**Spring Boot Expert** with full-stack capabilities in Java technologies  
🔹 Building robust REST APIs & microservices  
🔹 Implementing secure authentication systems  
🔹 Optimizing database performance  

## 🏢 Core Backend Stack
### Java Ecosystem:
![Spring Boot](https://img.shields.io/badge/-Spring_Boot-6DB33F?logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/-Spring_Security-6DB33F?logo=spring-security&logoColor=white)
![Hibernate](https://img.shields.io/badge/-Hibernate-59666C?logo=hibernate&logoColor=white)
![JPA](https://img.shields.io/badge/-JPA-59666C?logo=java&logoColor=white)

### API Development:
![REST API](https://img.shields.io/badge/-REST_API-FF6C37?logo=api&logoColor=white)
![Postman](https://img.shields.io/badge/-Postman-FF6C37?logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/-Swagger-85EA2D?logo=swagger&logoColor=black)

## 🛠️ Full Tech Stack
### Frontend:
![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-000000?logo=next.js&logoColor=white)

### Databases:
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?logo=mongodb&logoColor=white)



## 📈 GitHub Stats
![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=safi-sfn&show_icons=true&theme=radical)

## 🔥 Top Languages
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=safi-sfn&layout=compact&theme=radical)

## 📫 Let's Connect
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yourprofile)
[![Twitter](https://img.shields.io/badge/-Twitter-1DA1F2?logo=twitter&logoColor=white)](https://twitter.com/yourhandle)

## 🌟 Featured Spring Boot Projects

### 1. [E-Commerce Backend](https://github.com/safi-sfn/ecommerce-springboot)
![Spring Boot](https://img.shields.io/badge/-Spring_Boot-6DB33F?logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?logo=mysql&logoColor=white)
![JWT](https://img.shields.io/badge/-JWT-000000?logo=json-web-tokens&logoColor=white)
- Implemented RESTful APIs with Spring Web MVC
- Developed cart/order processing system
- Integrated Stripe payment gateway

### 2. [Hospital Management System](https://github.com/safi-sfn/hospital-spring)
![Spring Security](https://img.shields.io/badge/-Spring_Security-6DB33F?logo=spring-security&logoColor=white)
![Hibernate](https://img.shields.io/badge/-Hibernate-59666C?logo=hibernate&logoColor=white)
- Role-based access control (ADMIN/DOCTOR/PATIENT)
- Appointment scheduling system
- PDF report generation with Thymeleaf

### 3. [RESTful Microservices](https://github.com/safi-sfn/spring-microservices)
![Spring Cloud](https://img.shields.io/badge/-Spring_Cloud-6DB33F?logo=spring&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white)
- Service discovery with Eureka
- API Gateway with Spring Cloud Gateway
- Distributed configuration with Spring Cloud Config

## 🏢 Core Backend Stack
```java
@RestController
@RequestMapping("/api/v1")
public class ProductController {
    
    @Autowired
    private ProductService productService;
    
    @GetMapping("/products")
    public ResponseEntity<List<Product>> getAllProducts() {
        return ResponseEntity.ok(productService.findAll());
    }
}
