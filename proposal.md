# Propuesta aplicacion Concurso Jockey Club

## Creador
* Agustin España

### Repositorios
* [[frontend app](https://github.com/Agusesp1/APP-Concurso-frontend)]()
* [backend app]()

## Tema
### Descripción
*Aplicacion orientada a la inscripcion de participantes para el deporte equestre en donde permita asignar al participante inscripto a su/s concurso/s correspondiente/s*

### Modelo
![imagen del modelo]()


## Alcance Funcional 

### Alcance Mínimo


|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario<br>2. CRUD Participante<br>3. CRUD Concurso|
|CRUD dependiente|1. CRUD Concurso {depende de} CRUD participante<br>2. CRUD Cliente {depende de} CRUD Localidad|
|Listado<br>+<br>detalle| 1. Listado de inscriptos ... => detalle CRUD Habitacion<br> 2. Listado de reservas filtrado por rango de fecha, muestra nro de habitación, fecha inicio y fin estadía, estado y nombre del cliente => detalle muestra datos completos de la reserva y del cliente|
|CUU/Epic|1. Registrar la inscripcion del participante al Concurso|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad<br>4. CRUD Provincia<br>5. CRUD Habitación<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva<br>3. Realizar el check-out y facturación de estadía y servicios|


### Alcance Adicional

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio del concurso por email|
