## Frontend Don Bosco Airlines

![Logo](https://github.com/Raunier24/DonboscoApp/blob/dev/src/main/resources/Logo_F5_d_bosco_airlines.jpg)

# Team 4:
* Ana Maria Martin -------->> https://github.com/anamartin99
* Isamar Romero Bellorin -->> https://github.com/IsamarRB
* Abraham Martin Moya ----->> https://github.com/abmmm19888
* Raunier, Raunier24 ------>> https://github.com/Raunier24
* Jose M. Alonso Tirado ---->> https://github.com/jmatisam

# Project Context: 

## Descripción del Proyecto:

El proyecto tiene como objetivo desarrollar un sistema de gestión para una aerolínea utilizando una arquitectura monolítica basada en Spring Boot. Este sistema permitirá la gestión integral de usuarios, vuelos, reservas y destinos, con funcionalidades avanzadas como autenticación segura mediante JWT, eliminación automática de vuelos sin plazas disponibles o que hayan superado la fecha límite. El proyecto se implementará utilizando Java 17, Maven y MySQL, y se centrará en la modularidad, seguridad y eficiencia.


##  Objetivos del Proyecto:
1. Reforzar los conceptos de creación de APIs.
2. Aplicar relaciones de BBDD.
3. Gestión de datos mediante la gestión de la concurrencia.
4. Asentar conocimientos de login con Spring Security y JWT
5. Asentar conocimientos de GitHub Actions.

##  Requisitos funcionales del Proyecto:
* Gestión de Usuarios:
* Registro, autenticación y manejo de roles (ROLE_ADMIN y ROLE_USER).
* Generación y validación de tokens JWT para sesiones seguras.

##  Gestión de Vuelos:
* Los vuelos deben generarse automáticamente en base de datos al momento de compilación.
* Cambio de estado del vuelo disponible a “false” automáticamente cuando el vuelo quede sin plazas disponibles o fuera de fecha.

##  Gestión de Reservas:
* Crear reservas de vuelos solo si existe el trayecto seleccionado y si hay disponibilidad de plazas.
* Verificación de disponibilidad antes de confirmar una reserva.

## Gestión de Trayectos de vuelos:
* CRUD de destinos asociados a vuelos.
* Solo pueden gestionar los destinos el ROLE_ADMIN

## Consulta por Usuario:

* CRUD completo que podrá gestionar solo ROLE_ADMIN
* Deebemos poder obtener la lista del historial de reservas por cada usuario (ROLE_USER)

## Gestión de Excepciones:
* Poder manejar las excepciones de manera personalizada.

#  Requisitos No Funcionales

* Seguridad: Uso de Spring Security y JWT para proteger las APIs.
* Rendimiento: Optimizaciones como el cambio automático de estados de los  vuelos y la validación de reservas para mantener la eficiencia del sistema.
* Escalabilidad: Aunque es un sistema monolítico, se diseñará de manera que permita futuras expansiones o migración a una arquitectura de microservicios si es necesario.
* Disponibilidad: Implementación de Test para asegurar la estabilidad del sistema en producción.
* No se puede usar LOMBOK

Extras:
* Dockerizar y subir contenedor a Docker Hub
* Automatizar pruebas con Postman
* Aplicar patrón de diseño DTO
 
## ORM
![ORM](https://github.com/Raunier24/DonboscoApp/blob/feature/flight/src/main/resources/orm.jpg)
## Diagrama Spring Security
![KEY POINTS](https://github.com/Raunier24/DonboscoApp/blob/dev/src/main/resources/11.jpg)


## Panel de Administración del Frontend
![KEY POINTS]()

# Videos funcionamiento del Front
* [Presentación Front]()
* [Logeo OK]()

![KEY POINTS]()
## The documentation ;) Summary of the work carried out, in the Backend and the frontend.
## * [Documentación](https://www.canva.com/design/DAGRRwTYhYo/pbsLMFyFdP_47cmAtT1z3Q/view?utm_content=DAGRRwTYhYo&utm_campaign=designshare&utm_medium=link&utm_source=editor)
