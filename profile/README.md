# Sistema de Gestión Bancario - Documentación para el proyecto #4

¡Bienvenidos!
A continuación presento la documentación del sistema de gestión Bancario como parte del proyecto #4. Se ha desarrollado una arquitectura basada en microservicios para proporcionar soluciones eficientes y modernas en la gestión bancaria. En esta ocasión se estará utilizando Spring WebFlux, la cual nos ayudará para poder desarrollar de forma reactiva.
Del mismo modo se amplía las funcionalidades requeridas.

## Vista General

![Diagrama de Arquitectura](https://raw.githubusercontent.com/ProyectoSemana4-BC49/.github/main/res/diagram_proy4.png)

La imagen anterior ofrece una visión general de la arquitectura, donde cada microservicio cumple un papel crucial en la entrega de funcionalidades específicas. Del mismo modo, contempla otras herramientas usadas en el desarrollo de la solución. A continuación, proporciono detalles sobre cada repositorio que forma parte de este proyecto.

## Herramientas utilizadas

### CheckStyle
![Checkstyle](https://raw.githubusercontent.com/ProyectoSemana4-BC49/.github/main/res/checkstyle.PNG)

### Editor Swagger
![Sonarqube](https://raw.githubusercontent.com/ProyectoSemana4-BC49/.github/main/res/swagger.PNG)

### JaCoCo
![Sonarqube](https://raw.githubusercontent.com/ProyectoSemana4-BC49/.github/main/res/jacoco.PNG)

### ELK stack (Elasticsearch, Logstash y kibana)
###### Para el almacenamiento de logs
![Sonarqube](https://raw.githubusercontent.com/ProyectoSemana4-BC49/.github/main/res/logstash.jpeg)

### Apache Kafka
![kafka](https://raw.githubusercontent.com/ProyectoSemana4-BC49/.github/main/res/kafka_2.PNG)

### Redis
![redis](https://raw.githubusercontent.com/ProyectoSemana4-BC49/.github/main/res/redis.jpeg)

## Repositorios

### [ms-creditos](https://github.com/ProyectoSemana4-BC49/ms-creditos)
Este microservicio se centra en la gestión de operaciones relacionadas con créditos. Proporciona una API REST para la creación, actualización y consulta de información crediticia.

### [ms-cuentaBancaria](https://github.com/ProyectoSemana4-BC49/ms-cuentaBancaria)
Repositorio del microservicio de cuenta bancaria, desarrollado con Spring Boot. Contiene el código fuente, documentación y recursos asociados.

### [ms-customer](https://github.com/ProyectoSemana4-BC49/ms-customer)
Microservicio de Clientes: API para gestionar eficientemente la información de los clientes. Ofrece operaciones como creación, actualización, eliminación y consulta de detalles de clientes.

### [ms-monedero](https://github.com/ProyectoSemana4-BC49/ms-monedero)
Microservicio se encargará de gestionar todas las funcionalidades relacionadas con el monedero móvil, como la creación de cuentas de monedero, recepción y envío de pagos, y la asociación con tarjetas de débito.

### [Api-gateway](https://github.com/ProyectoSemana4-BC49/Api-Gateway)
Actúa como un API gateway, centralizando el enrutamiento y la gestión de peticiones para garantizar una comunicación eficiente entre microservicios.

### [config-server](https://github.com/ProyectoSemana4-BC49/config-server)
Funciona como un Config Server, centralizando la gestión de configuraciones para facilitar la actualización y distribución centralizada.

### [service-configuration](https://github.com/ProyectoSemana4-BC49/service-configuration)
Contiene configuraciones (.properties) de cada microservicio, facilitando la administración y el mantenimiento.

### [discovery-service](https://github.com/ProyectoSemana4-BC49/discovery-service)
Actúa como el server de Eureka para registrar los microservicios y permitir el descubrimiento dinámico.

## Cierre
Para concluir, si hay aspectos específicos que se requiira explorar en mayor detalle, mi correo electrónico personal: vertkle@gmail.com, para cualquier inquietud que pueda surgir.

Saludos cordiales,