# 🧩 **Challenge Foro Hub** 🧩

Foro Hub es una aplicación API de back-end diseñada para gestionar un foro de discusión. Permite a los 
usuarios registrarse, autenticarse y realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre 
los tópicos del foro, utilizando JWT para la seguridad. Esta aplicación está diseñado para facilitar la 
interacción entre usuarios que buscan resolver sus dudas y compartir conocimientos., utilizando Java, 
framework Spring Boot, MySQL.

![CRUD Principal](https://github.com/ZOECK17/ChallengeForoHub/blob/405e8042291128b9e6d2729d961330d5da6bb9aa/Imagenes/CRUD%20Principal.png)


## 💻 **Funcionalidades**
- POST /topicos/login: Autenticación de usuarios con nombre de usuario y contraseña.
- POST /topicos: Permite a los usuarios crear nuevos tópicos en el foro con su token generado.
- GET /topicos/listado: Muestra una lista de todos los tópicos disponibles.
- GET /topicos/{id}: Obtiene los detalles de un tópico específico mediante su ID.
- PUT /topicos/{id}: Permite la actualización de la información de un tópico existente.
- DELETE /topicos/{id}: Elimina tópicos no deseados del foro.

### POST /topicos/login:
![Autenticacion](https://github.com/ZOECK17/ChallengeForoHub/blob/405e8042291128b9e6d2729d961330d5da6bb9aa/Imagenes/Autenticacion.png)

#### POST /topicos:
![Registro Topico](https://github.com/ZOECK17/ChallengeForoHub/blob/405e8042291128b9e6d2729d961330d5da6bb9aa/Imagenes/Registro%20Topico.png)

#### GET /topicos/listado:
![Lista Topico](https://github.com/ZOECK17/ChallengeForoHub/blob/405e8042291128b9e6d2729d961330d5da6bb9aa/Imagenes/Lista%20Topicos.png)

### GET /topicos/{id}:
![Topico](https://github.com/ZOECK17/ChallengeForoHub/blob/405e8042291128b9e6d2729d961330d5da6bb9aa/Imagenes/Topico.png)

### PUT /topicos/{id}:
![Actualizar](https://github.com/ZOECK17/ChallengeForoHub/blob/405e8042291128b9e6d2729d961330d5da6bb9aa/Imagenes/Actualizar.png)

### DELETE /topicos/{id}:
![Eliminar](https://github.com/ZOECK17/ChallengeForoHub/blob/405e8042291128b9e6d2729d961330d5da6bb9aa/Imagenes/Eliminar.png)


## ⚙️ **Tenología utilizada**
```
Java 🔧
Maven 🔧
Spring Boot 🔧
Spring Data JPA 🔧
MySQL 🔧
JWT (JSON Web Tokens) 🔧
```
### ✔️ **Dependencias**

- Spring Data JPA  
- PostgreSQL Driver  
- Jackson-databind
- Lombok
- Flyway
- MySql-connector
- JWT
- Spring (web,security,validation,JPA)
- Versión Java SpringBoot (Initializr) 17

## ® **Hecho por:**
- Angel Ochoa
- Formación Java Spring Boot 3
- Alura Latam ONE G6 
- Oracle Next Education (ONE)
