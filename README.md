# springBoot2026 - Backend Spring Boot
---

## Project Information
```sh
project name: springBoot2026
author: Selim Cagan
spring boot version: ?   # pom.xml -> <parent> içindeki <version>
JDK: ?                   # pom.xml -> <java.version>
port: 5555
git url: https://github.com/Selimcagan32/springBoot2026.git
```
---

## Maven Compiler
```sh
mvn clean install
mvn clean package -DskipTests
```
---

## Run
```sh
mvn spring-boot:run
```
- Uygulama: http://localhost:5555
- H2 Console: http://localhost:5555/h2-console (JDBC URL: `jdbc:h2:file:./database_memory_persist/blog`, Username: `sa`, Password: boş)
---

## Git Clone
```sh
git clone https://github.com/Selimcagan32/springBoot2026.git
```
---

## Git Codes
```sh
git init
git add .
git commit -m "git init"
git branch -M main
git remote add origin https://github.com/Selimcagan32/springBoot2026.git
git push -u origin main

git status
git log
```
---
