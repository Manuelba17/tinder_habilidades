# Modelado de tinder para habilidades
API que permita buscar personas según sus habilidades

## listado de entidades 

### Usuarios 

- numero_identificacion **PK**
- nombre
- apellidos
- habilidades
- valor_hora
- telefono

### Empresas

- nit **PK**
- nombre
  

### Cotizaciones

- cotizacion_id **PK**
- nit **FK**
- numero_identificacion **FK**
- horas_contratadas
- direccion
- dia_hora
- estado_cotizacion
- fecha_cotizacion

### Pagos

- numero_trx **PK**
- cotizacion_id **FK**
- anticipacion
- pago_total
  

### Calificaciones

- calificacion_id **PK**
- cotizacion_id **FK**
- obeservacion
