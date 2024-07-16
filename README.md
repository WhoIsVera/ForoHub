# ForoHub

ForoHub es una aplicación web diseñada para facilitar la creación y gestión de foros de discusión. Los usuarios pueden crear tópicos, responder a otros usuarios y explorar cursos relacionados.

## Características

- **Registro de Usuarios**: Permite a los usuarios registrarse y acceder a la plataforma.
- **Creación de Tópicos**: Los usuarios pueden iniciar nuevos tópicos de discusión.
- **Respuestas a Tópicos**: Permite a los usuarios responder a los tópicos existentes.
- **Gestión de Cursos**: Los cursos pueden ser creados y asociados con tópicos.
- **Autenticación y Seguridad**: Implementa seguridad mediante JWT y Spring Security.

## Tecnologías Utilizadas

- **Java**: Lenguaje de programación principal.
- **Spring Boot**: Framework para el desarrollo de aplicaciones.
- **Spring Security**: Manejo de la autenticación y autorización.
- **JPA/Hibernate**: Acceso a datos y gestión de la base de datos.
- **Base de Datos**: PostgreSQL (o la que se especifique).
- **Lombok**: Para simplificar el código Java.

## Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/WhoIsVera/ForoHub.git

## Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/WhoIsVera/ForoHub.git

## Configura tu base de datos en `application.properties`

    Abre el archivo `src/main/resources/application.properties` y configura los siguientes parámetros de conexión a tu base de datos:
    
    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/tu_base_de_datos
    spring.datasource.username=tu_usuario
    spring.datasource.password=tu_contraseña
    spring.jpa.hibernate.ddl-auto=update
    spring.jpa.show-sql=true
    
## Ejecuta la aplicación

    Para iniciar la aplicación, asegúrate de tener Maven instalado y ejecuta el siguiente comando en el directorio raíz del proyecto:
    
    ```bash
    mvn spring-boot:run

## Uso

    1. **Registro de Usuarios**: Los usuarios pueden registrarse proporcionando un nombre, correo electrónico y contraseña.
    
    2. **Inicio de Sesión**: Los usuarios pueden iniciar sesión utilizando sus credenciales registradas para acceder a las funcionalidades del foro.
    
    3. **Crear un Tema**: Los usuarios autenticados pueden crear nuevos tópicos en diferentes cursos, proporcionando un título, mensaje y seleccionando el curso correspondiente.
    
    4. **Actualizar un Tema**: Los usuarios pueden actualizar sus tópicos existentes, modificando el título, mensaje y otros atributos.
    
    5. **Consultar Tópicos**: Los usuarios pueden ver una lista de tópicos existentes, con información sobre el autor, curso, y detalles del mensaje.
    
    6. **Respuestas**: Los usuarios pueden responder a tópicos, proporcionando su mensaje y asociándolo al tópico correspondiente.
    
    



