# Spring Boot API REST : Construindo uma API

+ Criando aplicação Java com o Spring Boot.
+ Configurando a aplicação Spring sem o uso de arquivos XML.
+ Aprendendo o estilo arquitetural REST.
+ Uso de Spring Data e Bean Validation.

<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/><img src="https://img.shields.io/badge/Spring_Boot-F2F4F9?style=for-the-badge&logo=spring-boot"/><img src = "https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white"/>

## Requirements

1. Java - 1.8.x
<img src = "https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"/>
2. Maven - 3.x.x - 
<img src="https://img.shields.io/badge/apache_maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" />
3. Eclipse - 2021
<img src= "https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipse&logoColor=white"/>

## Passos para o SETUP

**1. Clone a aplicação**

```bash
git clone https://github.com/virginia-silva/API-REST---JAVA.git
```

**2. Modifique o usuário e senha de acordo com a sua instalação**

+ abra `src/main/resources/application.properties`

+ modifique `spring.datasource.username` e `spring.datasource.password` de acordo com sua instalação

**3. Build e rode a aplicação usando MAVEN**

```bash
mvn package
java -jar target/crud-1.0.0.jar
```

Alternativamente, você pode rodar dessa forma -

```bash
mvn spring-boot:run
```

O app vai rodar nesse endereço <http://localhost:8080>.

## Explore as APIs

Você pode testar as APIs utilizando o Postman...
