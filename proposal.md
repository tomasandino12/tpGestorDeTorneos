# Propuesta TP DSW

## Grupo
### Integrantes
* 52995 - Tomás, Andino
* legajo - Burgos, Mateo
* 52991 - Negri, Geronimo

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
### Descripción
El proyecto consiste en una aplicación web para la gestión de torneos deportivos amateur. Permite registrar jugadores y equipos, crear torneos con su respectivo fixture, cargar resultados de partidos y visualizar automáticamente las tablas de posiciones y estadísticas del torneo. Ideal para clubes, grupos de amigos o ligas barriales que deseen organizar sus competencias de forma simple y ordenada.

### Modelo
![imagen del modelo]()

*Nota*: incluir un link con la imagen de un modelo, puede ser modelo de dominio, diagrama de clases, DER. Si lo prefieren pueden utilizar diagramas con [Mermaid](https://mermaid.js.org) en lugar de imágenes.

## Alcance Funcional 

### Alcance Mínimo
 El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Jugador<br>2. CRUD Cancha<br>3. CRUD Arbitro|
|CRUD dependiente|1. CRUD Equipo {depende de} CRUD Partidos<br>2. CRUD Torneo {depende de} CRUD Equipo|
|Listado<br>+<br>detalle| 1. Listado de equipos filtrados por sus puntos y partidos jugados  => detalle CRUD Habitacion<br> 2. Listado de oartidos ffiltados por fecha mostrando el rival el horario y la cancha => detalle muestra datos completos de la reserva y del cliente|
|CUU/Epic|1. Ver los partidos y sus estadisticas<br>2. Cargar equipos y jugadores|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad<br>4. CRUD Provincia<br>5. CRUD Habitación<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva<br>3. Realizar el check-out y facturación de estadía y servicios|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|

