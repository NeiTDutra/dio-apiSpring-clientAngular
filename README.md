# Chat Room

## [API Spring](https://github.com/NeiTDutra/dio-apiSpring-clientAngular/tree/master/Api-Spring/chatroom) / [Client Angular](https://github.com/NeiTDutra/dio-apiSpring-clientAngular/tree/master/Client-Angular)

Projeto desenvolvido no bootcamp *Santander FullStack Developer - Digital Innovation One Inc.*

*"Crie seu gerenciador de salas de reuniões com Java/Spring e Angular"*

Projeto Angular bifurcado de [Kamilahsantos/Client-Angular-Live-Coding-Dio](https://github.com/Kamilahsantos/Client-Angular-Live-Coding-Dio)

## Escopo

Desenvolvimento de API com Spring / Java para agendar data e hora de evento

Desenvolvimento de cliente web com Angular para utilizar a api: criar, listar, editar e excluir eventos

## Tecnologias

*Dependências da api Spring*

```xml

<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
 xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 https://maven.apache.org/xsd/maven-4.0.0.xsd">
 <modelVersion>4.0.0</modelVersion>
 <parent>
  <groupId>org.springframework.boot</groupId>
  <artifactId>spring-boot-starter-parent</artifactId>
  <version>2.5.2</version>
  <relativePath/> <!-- lookup parent from repository -->
 </parent>
 <groupId>com.api.chat</groupId>
 <artifactId>chatroom</artifactId>
 <version>0.0.1-SNAPSHOT</version>
 <name>chatroom</name>
 <description>Demo project for Spring Boot</description>
 <properties>
  <java.version>11</java.version>
 </properties>
 <dependencies>
  <dependency>
   <groupId>org.springframework.boot</groupId>
   <artifactId>spring-boot-starter-data-jpa</artifactId>
  </dependency>
  <dependency>
   <groupId>org.springframework.boot</groupId>
   <artifactId>spring-boot-starter-web</artifactId>
  </dependency>

  <dependency>
   <groupId>com.h2database</groupId>
   <artifactId>h2</artifactId>
   <scope>runtime</scope>
  </dependency>
  <dependency>
   <groupId>org.projectlombok</groupId>
   <artifactId>lombok</artifactId>
   <optional>true</optional>
  </dependency>
  <dependency>
   <groupId>org.springframework.boot</groupId>
   <artifactId>spring-boot-starter-test</artifactId>
   <scope>test</scope>
  </dependency>
  <dependency>
   <groupId>jakarta.validation</groupId>
   <artifactId>jakarta.validation-api</artifactId>
   <version>2.0.2</version>
  </dependency>
 </dependencies>

 <build>
  <plugins>
   <plugin>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-maven-plugin</artifactId>
    <configuration>
     <excludes>
      <exclude>
       <groupId>org.projectlombok</groupId>
       <artifactId>lombok</artifactId>
      </exclude>
     </excludes>
    </configuration>
   </plugin>
  </plugins>
 </build>

</project>

```

*Dependências client side Angular*

```json

{
  "name": "client-room",
  "version": "0.0.0",
  "scripts": {
    "ng": "ng",
    "start": "ng serve",
    "build": "ng build",
    "test": "ng test",
    "lint": "ng lint",
    "e2e": "ng e2e"
  },
  "private": true,
  "dependencies": {
    "@angular/animations": "~9.0.0-rc.7",
    "@angular/common": "~9.0.0-rc.7",
    "@angular/compiler": "~9.0.0-rc.7",
    "@angular/core": "~9.0.0-rc.7",
    "@angular/forms": "~9.0.0-rc.7",
    "@angular/platform-browser": "~9.0.0-rc.7",
    "@angular/platform-browser-dynamic": "~9.0.0-rc.7",
    "@angular/router": "~9.0.0-rc.7",
    "bootstrap": "4.5.0",
    "jquery": "3.5.1",
    "rxjs": "~6.5.3",
    "tslib": "^1.10.0",
    "zone.js": "~0.10.2"
  },
  "devDependencies": {
    "@angular-devkit/build-angular": "~0.900.0-rc.7",
    "@angular/cli": "~9.0.0-rc.7",
    "@angular/compiler-cli": "~9.0.0-rc.7",
    "@angular/language-service": "~9.0.0-rc.7",
    "@types/node": "^12.11.1",
    "@types/jasmine": "~3.5.0",
    "@types/jasminewd2": "~2.0.3",
    "codelyzer": "^5.1.2",
    "jasmine-core": "~3.5.0",
    "jasmine-spec-reporter": "~4.2.1",
    "karma": "~4.3.0",
    "karma-chrome-launcher": "~3.1.0",
    "karma-coverage-istanbul-reporter": "~2.1.0",
    "karma-jasmine": "~2.0.1",
    "karma-jasmine-html-reporter": "^1.4.2",
    "protractor": "~5.4.2",
    "ts-node": "~8.3.0",
    "tslint": "~5.18.0",
    "typescript": "~3.6.4"
  }
}

```

:construction: Em desenvolvimento... :construction:
