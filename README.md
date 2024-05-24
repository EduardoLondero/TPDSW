# Propuesta TP DSW

## Grupo
### Integrantes
* 51708 - Londero, Eduardo Agustin
* 50936 - Ojeda, Alejo Agustin
  
### Repositorios
* [frontend app](https://github.com/EduardoLondero/club-frontend)
* [backend app](https://github.com/EduardoLondero/club-backend)

## Tema
### Descripción
Nuestro proyecto consiste en una aplicación web centrada en la administración y gestion de las membresias de un club deportivo.

### Modelo
[Imagen](https://imgur.com/3kPFe6k)

## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tipo Membresia<br>2. CRUD Deporte<br>3. CRUD Localidad|
|CRUD dependiente|1. CRUD Membresia {depende de} CRUD Tipo Membresia<br>2. CRUD Cliente {depende de} CRUD Localidad|
|Listado<br>+<br>detalle| 1. Listado de Membresias filtrado por tipo de Membresia. Muestra id y tipo de Membresia => detalle CRUD Membresia<br> 2. Listado de Membresias por rango de fecha de vencimiento, muestra id, fecha inicio de pago y vencimiento, estado y nombre del cliente => detalle muestra datos completos de la Membresia y del cliente|
|CUU/Epic|1. Comprar Membresia<br>2. Verificación de Membresia|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Membresia<br>2. CRUD Deporte<br>3. CRUD Localidad<br>4. CRUD Barrio<br>5. CRUD Membresia<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Comprar Membresia<br>2. Verificación de Membresia<br>3. Realizar factura|


### Alcance Adicional Voluntario

|Req|Detalle|
|:-|:-|
|Listados |1. Concurrencia del dia filtrada por fecha, muestra cliente, Membresia y deporte <br>2. Membresias filtradas por cliente, muestra datos del cliente, y de cada Membresia: fechas, estado del pago, deportes|
|CUU/Epic|1. Consumir servicio de deporte<br>2. Cancelación de Membresia|
|Otros|1. Envío de recordatorio de vencimiento por email|
