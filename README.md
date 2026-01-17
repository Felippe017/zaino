# Zaino E-Commerce

Este é um projeto de e-commerce chamado **Zaino**.

---

## Descrição

Zaino é uma aplicação de comércio eletrônico desenvolvida com Spring Boot.

---

## Tecnologias

- Java
- Spring Boot
- Maven

---

## Como executar

### Pré-requisitos

- Java 17 ou superior
- Maven 3.6+ (ou usar o Maven Wrapper incluído no projeto)

### Executando o projeto

1. Clone o repositório:
```bash
git clone <url-do-repositorio>
cd zaino
```

2. Execute o projeto usando o Maven Wrapper:
```bash
./mvnw spring-boot:run
```

Ou no Windows:
```bash
mvnw.cmd spring-boot:run
```

3. A aplicação estará disponível em `http://localhost:8080`

### Compilando o projeto

Para compilar o projeto e gerar o arquivo JAR:
```bash
./mvnw clean package
```

O arquivo JAR será gerado em `target/Zaino_ECommerce-0.0.1-SNAPSHOT.jar`

Para executar o JAR:
```bash
java -jar target/Zaino_ECommerce-0.0.1-SNAPSHOT.jar
```

---

## Autor

Projeto desenvolvido por Lucas Lotar e Felippe Correa como.


