# Web Services REST con Jersey

## Objetivo
Este proyecto tiene como objetivo demostrar la implementación de servicios web REST utilizando Jersey en un proyecto Maven. Se cubren aspectos clave como la configuración del entorno, la definición del modelo de datos y la exposición de servicios REST.

## Presentación
El desarrollo se centra en la creación de un servicio web RESTful dentro de un proyecto Maven, haciendo uso del framework Jersey. Se aborda la configuración del `web.xml`, la implementación de servicios mediante anotaciones y la prueba de la API con Postman.

## Desarrollo
### Creación del Proyecto Maven Web
- Configuración inicial del proyecto en Maven.
- Definición de las dependencias necesarias en el `pom.xml`, incluyendo la librería Jersey.
- Configuración del servidor web para la ejecución de la aplicación.

### Configuración del Web.xml
- Creación del archivo `web.xml` para establecer la configuración del servlet de Jersey.
- Definición de los paquetes donde se encuentran los servicios REST.
- Habilitación del soporte JSON con la configuración adecuada.

### Definición del Modelo de Datos
- Creación de la clase `Person` con atributos básicos.
- Generación de métodos `get` y `set` para manipulación de datos.
- Anotación de la clase para representación en formato XML y JSON.

### Implementación de Servicios REST
- Creación de la clase `Service` para definir los métodos de la API.
- Implementación de los métodos `GET`, `POST` para interactuar con el modelo de datos.
- Uso de anotaciones como `@Path`, `@GET`, `@POST` para definir rutas y tipos de respuesta.

### Ejecución y Pruebas
- Configuración y despliegue del servidor web.
- Prueba de los endpoints mediante un navegador web y Postman.
- Verificación de respuestas en formato JSON y XML.

## Ejemplo de Funcionamiento
1. Se inicia el servidor web y se accede a la API.
2. Se consulta la lista de personas en formato JSON y XML.
3. Se agrega una nueva persona mediante un request `POST` en Postman.
4. Se verifica la correcta adición consultando nuevamente la API.


![image](https://github.com/user-attachments/assets/06c8bdd2-bb0b-49a2-a42e-04fff5da524a)
![image](https://github.com/user-attachments/assets/c53fadd1-6c13-407c-9c11-9e0b1e01c7d3)
![image](https://github.com/user-attachments/assets/78c052fc-be43-4819-9187-3a8bb5940d54)




## Conclusión
Este proyecto muestra cómo implementar servicios web RESTful en Java utilizando Jersey. Se aborda desde la configuración del entorno hasta la exposición y prueba de servicios, facilitando la integración con aplicaciones externas.

## Referencias
- [Documentación oficial de Jersey](https://eclipse-ee4j.github.io/jersey/)
- [Guía de servicios REST en Java](https://docs.oracle.com/javaee/7/tutorial/jaxrs.htm)

