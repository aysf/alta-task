# Golang Backend Task 
Here I put tasks of Golang Backend Bootcamp from Alterra Academy in part section as submodule repository. 
Feel free to ask if there are some that you could not understand.

## Week 3: Relational Database 
### Part 1: Schema Database
### Part 2: Data Definition Language (DDL)
### Part 3: Data Manipulation Language (DML)

## Week 4: RESTful API with Go
### Part 1: Introduction to Postman
### Part 2: Create Static API CRUD User
### Part 3 (problem 1): API CRUD User using database

## Week 5: Code Structuring (cont.)
### Part 3 (Problem 2): MVC Code Structuring
### Part 4: Middleware, Logging and JWT Authentication

## Week 6: Unit Testing
### Part 1: Unit Testing Implementation

## Week 7: AltaStore Project
### Part 1: API AltaStore Project

## Week 8: Deploy
### Part 1: Docker
1. Install docker & docker compose
2. Create dockerfile
3. Clone your code and integrate to your dockerfile
4. Build your container
5. Push the image to docker registry
6. Deploy in your local machine
7. Try DockerCompose to run go app + mysql(opt)
8. Try to Deploy in the Cloud(opt)

### Part 2: Membuat VM di EC2 
1. Membuat VM di EC2 dan implementasi security group EC2
2. Melakukan SSH Remote ke VM di AWS EC2 (dengan key) serta dijelaskan key dan password using `ssh -i path/to/*.pem user@public_ip_address` 
3. Transfer file using `scp -i path/to/*.pem path/to/file.target user@public_ip_address:path/to/destination`
4. deploy your program to EC2.

### Part 3: Deployment RDS
1. Membuat DB di RDS
2. Migrate your local data to RDS
3. Connect your application to RDS

### Part 4: Pointing Domain
1. Pointing Domain ke IP VM EC2
2. Deploy dan jalankan aplikasi di live environment di AWS yang dapat diakses publik sesuai standard

### Part 5: Deployment CI/CD
1. Create CI/CD to automate deployment https://github.com/iffakhry/alta-aws-ec2-be2

### Part 6: Deployment Kubernetes
1. Deploy your application by using kubectl from your local machine
    a. Containerize go app (docker build)
    b. Push to image registry (docker push)
    c. Create kubernetes manifest
    d. Try to perform kubectl appyl
3. Create CI/CD to automate deployment with Kubernetes
