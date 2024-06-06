# Desafío: Integración Backend-Frontend

## Descripción del Desafío

El objetivo de este desafío es crear una aplicación que gestione una base de datos de películas. La base de datos contendrá información sobre el nombre de la película, la fase a la que pertenece y su autor. La aplicación permitirá a los usuarios consumir esta información de forma aleatoria en el frontend.

## Recursos y Tecnologías Utilizadas

- **Backend**: Spring Framework
  - Dependencias adicionales: JPA, Lombok, Web, y DevTools
  - Lenguaje: Java 17
- **Frontend**: HTML, CSS, y JavaScript
- **Base de Datos**: PostgreSQL

## Instrucciones para Ejecutar el Proyecto

1. **Clonar el Repositorio**:
    ```bash
    git clone https://github.com/lau1999/desafio-integracion-backend-frontend-curso.git
    ```

2. **Importar la Base de Datos**:
    - Sigue las instrucciones en este [video tutorial](https://www.youtube.com/watch?v=icEvkyIXqug) para importar la base de datos.

3. **Instalar Java 17**:
    - Asegúrate de tener instalado Java 17. Si no lo tienes, sigue las instrucciones en este [video tutorial](https://www.youtube.com/watch?v=BG2OSaxWX4E).

4. **Configurar el Proyecto**:
    - Asegúrate de tener PostgreSQL instalado y ejecutándose.
    - Configura la conexión a la base de datos en el archivo `application.properties` en el directorio `src/main/resources` del proyecto.
    
    Ejemplo de configuración:
    ```properties
    spring.datasource.url=jdbc:postgresql://localhost:5432/nombre_de_tu_base_de_datos
    spring.datasource.username=tu_usuario
    spring.datasource.password=tu_contraseña
    spring.jpa.hibernate.ddl-auto=update
    ```

5. **Ejecutar el Backend**:
    - Navega al directorio del proyecto y ejecuta el siguiente comando para iniciar el servidor Spring Boot:
    ```bash
    ./mvnw spring-boot:run
    ```

6. **Ejecutar el Frontend**:
    - Abre el archivo `index.html` en un navegador web.

## Funcionalidades Esperadas

- **Backend**:
  - Endpoints RESTful.
  - Manejo de la lógica de negocio y acceso a la base de datos.

- **Frontend**:
  - Interfaz de usuario para interactuar con el backend.
  - Formulario para la entrada de datos y visualización de los resultados.

## Conclusión

Este desafío es una excelente oportunidad para demostrar tus habilidades en la integración de tecnologías backend y frontend, así como en la gestión y configuración de una base de datos. ¡Buena suerte!

## Resultado

![Resultado](https://github.com/lau1999/desafio-integracion-backend-frontend-curso/assets/135270242/77d2cf44-6303-475c-a2c6-21b0e9be15f1)
