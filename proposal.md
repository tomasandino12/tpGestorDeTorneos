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
![modelo de dominio ](https://github.com/user-attachments/assets/30b0e679-b2fe-4bd5-9c17-b9ae8fb7a381)


## Alcance Funcional 

### Alcance Mínimo
Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Jugador<br>2. CRUD Cancha<br>3. CRUD Arbitro|
|CRUD dependiente|1. CRUD Equipo {depende de} CRUD Jugador<br>2. CRUD Torneo {depende de} CRUD Equipo|
|Listado<br>+<br>detalle| 1. Listado de equipos filtrados por sus puntos y partidos jugados, muestra posición, nombreEquipo, puntos, partidos jugados empatados ganados y perdidos y diferencia de gol  => detalle muestra datos del equipo como sus jugadores y historial de partidos<br> 2. Listado de partidos filtrados por fecha mostrando el rival el horario y la cancha => detalle muestra datos del equipo y jugadores|
|CUU/Epic|1. Ver los partidos y sus estadisticas<br>2. Cargar equipos y jugadores|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Jugador<br>2. CRUD Cancha<br>3. CRUD Arbitro<br>4. CRUD Equipo<br>5. CRUD Torneo<br>6. CRUD Partido<br>7. CRUD Administrador|
|CUU/Epic|1.Ver los partidos y sus estadisticas<br>2. Crear torneos<br>3. Asignar partidos para equipo|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Jugadores con mas asistencias del torneo <br>2. Jugadores con mas goles del torneo|
|CUU/Epic|1. Cambiar de equipo (con aprobación)<br>2. Cargar estadisticas de jugador|
|Otros|1. Gestion de arbitros, equipos y canchas|

