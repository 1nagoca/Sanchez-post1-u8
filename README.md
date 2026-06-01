# CRUD Estudiantes - UFPS
**Asignatura:** Programación Web (Unidad 8)  
**Estudiante:** [Tu Nombre y Apellido] | **Código:** [Tu Código]

Este proyecto es un sistema CRUD para gestionar estudiantes usando **Spring Boot 3**, **Spring Data JPA**, **Hibernate** y **MySQL**, renderizado con **Thymeleaf**.

---

## 1. Configuración de la Base de Datos
Ejecuta estos comandos en tu gestor de MySQL para crear la base de datos y el usuario con los accesos exactos que requiere el proyecto (`application.properties`):

```sql
CREATE DATABASE estudiantes_db CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
CREATE USER 'appuser'@'localhost' IDENTIFIED BY 'apppass';
GRANT ALL PRIVILEGES ON estudiantes_db.* TO 'appuser'@'localhost';
FLUSH PRIVILEGES;
```
## 2. Ejecución del Proyecto
Abre la terminal en la raíz del proyecto.
Ejecuta el comando: ./mvnw spring-boot:run
Entra desde tu navegador a: http://localhost:8080/estudiantes

## 3. Evidencias de Funcionamiento
Vista Principal (Lista de Estudiantes)
Validaciones y Control de Errores
Correo Inválido (Formato)
Correo Duplicado (Restricción)
