# 🎉✨ **¡Bienvenido a ForoHub!** ✨🎉
## 🌟 **Oracle y Alura Challenge** 🌟

🚀 ForoHub es una aplicación web desarrollada en **Java** con **Spring Boot** para gestionar tópicos en un foro, una solución para el cuarto desafío de programación de **Oracle Next Generation (ONE)** de **Alura**. ¡Permite a los usuarios autenticados crear, listar, actualizar y eliminar tópicos!

---

## 🔥 **Características** 🔥

- 📝 **Gestión de tópicos**: Crea, lee, actualiza y elimina tópicos en el foro.
- 🔐 **Autenticación de usuarios**: Solo usuarios autenticados pueden interactuar con la API.
- 💾 **Persistencia de datos**: Utiliza PostgreSQL para almacenar datos.
- 🔄 **Migraciones de base de datos**: Flyway para gestionar cambios en el esquema de la base de datos.
- ✔️ **Validación de datos**: Asegura la calidad de los datos mediante validaciones.
- 📚 **Documentación de API**: Swagger UI para explorar y probar los endpoints de la API.

---

## 🛠️ **Tecnologías** 🛠️

- ☕ **Java**: Versión 21.
- 📦 **Maven**: Gestión de dependencias y construcción del proyecto.
- ⚙️ **Spring Boot**: Framework para desarrollar la aplicación. Versión 3.
- 🐘 **PostgreSQL**: Sistema de gestión de bases de datos. Versión 16.
- 📜 **Flyway**: Migraciones de base de datos.
- 🛡️ **Spring Security**: Seguridad y autenticación de usuarios.

---

## 📂 **Estructura del Proyecto** 📂

- **config**: Configuraciones de Spring Boot, incluyendo la configuración de seguridad.
- **controller**: Controladores REST que gestionan las solicitudes de la API.
- **model**: Clases de modelo que representan las entidades de la base de datos.
- **repository**: Repositorios para acceder a los datos en la base de datos.
- **service**: Lógica de negocio de la aplicación.
- **dto**: Clases de transferencia de datos (DTO) para las solicitudes y respuestas de la API.

---

## 📊 **Diagrama de Base de Datos** 📊

> Este diagrama es una referencia; puedes adaptar la estructura según tus necesidades.

---

## 🔄 **Migraciones con Flyway** 🔄

Flyway se encarga de aplicar los scripts SQL en orden. Asegúrate de mantener el orden de las migraciones y crear los archivos en el directorio `src/main/resources/db/migration`.

### Comandos Útiles de Flyway

- 🧹 Limpiar la Base de Datos:
  ```sh
  mvn flyway:clean
