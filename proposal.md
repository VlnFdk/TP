# Propuesta TP DSW

## Grupo
### Integrantes
* 48706 - Feldkircher, Valentin
* 46166 - Borelli, Hernán
* 51550 - Falcon, Ramiro
* 48033 - Fernandez, Martina

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
### Descripción
Sistema para administración de edificios. El objetivo del sistema es proporcionar una plataforma que facilite a los usuarios la gestión de distintos tipos de inmuebles. De manera preeliminar los usuarios del sistema podrian tener alguno de los siguientes roles: Administrador, Personal de mantenimiento y Residente. El sistema permitira gestionar el uso y mantenimiento de áreas comunes, el pago y liquidacion de expensas, reporte de problemas y notificación de vencimientos.


### Modelo
[Modelo](https://drive.google.com/drive/folders/1i3ZkWKXsX78iOBaCGWFN849ChEIzCFs0)

![Modelo_TP_DSW drawio](https://github.com/user-attachments/assets/c3e62a28-1dee-4345-ba8c-20a2894c547b)



## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tipo Usuario <br>2. CRUD Tipo Inmueble<br>3. CRUD Edificio<br>4. CRUD Tipo Área Común| 
|CRUD dependiente|1. CRUD Usuario {depende de} CRUD Tipo Usuario <br>2. CRUD Incidencia {depende de} CRUD Área Común|
|Listado<br>+<br>detalle| 1. Listado de expensas filtrado por tipo de expensas, muestra mes,año y tipo de expensas => detalle CRUD Expensas<br> 2. Listado de reservas de Áreas comunes filtrado por rango de fecha, muestra Tipo Área Común, hora inicio y fin reserva, estado y nombre del Residente => detalle muestra datos completos de la reserva y del Residente|
|CUU/Epic|1. Reservar un Área Común para un Residente <br>2. Registrar una incidencia de un Área Común|


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

