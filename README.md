# Mis Apuntes

Este repositorio contiene una colección de apuntes y guías sobre diversas tecnologías y buenas prácticas en el desarrollo de software. Estos documentos han sido creados con el objetivo de proporcionar referencias rápidas y claras para configurar y utilizar herramientas comunes en proyectos de software.

## Contenido

### 1. [Comandos Importantes GIT](./Comandos%20Importantes%20GIT.txt)

Este documento cubre comandos esenciales de Git, incluyendo:
- Inicialización de un repositorio.
- Vinculación de un repositorio local con GitHub.
- Buenas prácticas para escribir mensajes de commit claros y descriptivos.

### 2. [Cómo Funciona Spring Security](./Como%20funciona%20Spring%20Security.txt)

Explicación del flujo de autenticación en Spring Security, incluyendo:
- Proceso de autenticación.
- Authentication Manager y Authentication Provider.
- Uso de UserDetailsService y contexto de seguridad.

### 3. [Dockerizar API y DB](./Dockerizar-API-DB.txt)

Guía para empaquetar una API de Spring Boot y configurar bases de datos con Docker Compose:
- Configuración de `application.properties` con variables de entorno.
- Creación del Dockerfile para la API de Spring Boot.
- Creación del archivo `docker-compose.yml` para la API y PostgreSQL.
- Pasos para construir y desplegar los servicios con Docker Compose.

### 4. [Ejecutar una API de Docker-Hub](./Ejecutar%20una%20API%20de%20Docker-Hub.txt)

Pasos para ejecutar una API de Spring Boot y una base de datos PostgreSQL descargadas desde Docker Hub:
- Creación de una red Docker.
- Ejecución de contenedores PostgreSQL y Spring Boot en la red Docker.
- Conexión a la base de datos dentro del contenedor.

### 5. [Mis Bases de Datos en Docker](./Mis%20Bases%20de%20Datos%20en%20Docker.txt)

Configuración y ejecución de bases de datos MySQL, Oracle SQL y PostgreSQL utilizando Docker Compose:
- Contenido de los archivos `docker-compose.yml` para cada base de datos.
- Ejecución de los contenedores.
- Configuración de `application.properties` en proyectos Spring Boot para conectarse a las bases de datos.

### 6. [Mis Bases de Datos](./Mis%20Bases%20de%20Datos.txt)

Conexiones a cuatro bases de datos relacionales (MySQL, PostgreSQL, Oracle y H2) con credenciales preestablecidas:
- Detalles de conexión para cada base de datos.
- Configuración de JPA/Hibernate para Spring Boot.

## Uso

Para utilizar cualquiera de los apuntes, simplemente navega al archivo correspondiente y sigue las instrucciones proporcionadas. Estos documentos están diseñados para ser una referencia rápida y útil para desarrolladores trabajando en diversos proyectos.
