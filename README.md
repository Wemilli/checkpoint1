# Microservices and Web Engineering
- Sistema de agenda de consultas

## 📌 Estrutura do Projeto   

### 📂 **Model**  
Contém as entidades do sistema, que representam as tabelas do banco de dados.  

### 📂 **DTO (Data Transfer Object)**  
Utilizado para transferir dados entre camadas sem expor diretamente as entidades do banco.  

### 📂 **Service**  
Responsável pela lógica de negócio do sistema, incluindo validações e regras antes de acessar o banco de dados.  

### 📂 **Controller**  
Gerencia as requisições HTTP, direcionando as chamadas para a camada de serviço e retornando as respostas adequadas.  


## 🛠️ Instalação

* Limpar e criar a pasta */target*

```
mvn clean package
```

* Configuração do Swagger

    - https://springdoc.org/properties.html

- application.properties

```
springdoc.swagger-ui.path=/
springdoc.swagger-ui.disable-swagger-default-url=true
```


## 🌐 Navegação

### Executar a API

-  *Executando* **Maven**

```
mvn spring-boot:run
```

### Documentação da API (Swagger)
- http://localhost:8080/


## Referencias

- https://springdoc.org/
