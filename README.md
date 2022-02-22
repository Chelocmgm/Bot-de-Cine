
# Proyecto BOT de cine 
## Introduccion 
Este documento especifica el porque es necesario tener un BOT  para **Reserva de tickets de un cine**
## Problematica

La empresa de cine HIGH SCHOOL MUSICAL, cuanta con 10 empleados entre los cuales se encuentran desde el personal de limpiaza hasta los cajeros que hacen la venta de las entradas por lo cual se generaron los siguientes problemas:
## Problematica en la empresa

1. El cine solo tiene un cajero.
2. El cine pierde mucha clientela debido a la larga espera para la compra
   de tickets
3. El lobby genera mucha conglomeracion de gente a la hora de la 
   compra de ticket.
4. La conglomeracion de gente hace que el cine genere
   mayor cantidad de basura y suciedad.
5. La persona encargada de ventas tiene mucha 
   carga de trabajo a la hora de la venta de los tickets.
6. Cuando exite mucha demanda de una pelicula existen riesgos de no haber 
   hecho un buen control de la compra de tickets.

## Problematica en el cliente

1. Existe una mayor exposicion a contagios contra el virus COVID 19
   en el control de filas.
2. El cliente no tiene mucho informacion hacia la cartelera.
3. El cliente pierde mucho tiempo haciendo filas.

## El valor del proyecto hacia la empresa

- Tangible
 - Evitara la perdida de clientes por largas filas.
 - Mejor administración en ventas.
 - Mayor contron en las salas de cine.
 - Mejor gestion sobre el personas del cine.
- Intangibles
 - Mayor seguridad hacia los empleados y clientes contra contagios.
 - Perdida de tiempo en la limpieza.

## Ejemplo de funcionamiento de Bot

### Menu cliente

Cliente: Hola
Bot: Hola como puedo ayudarte?
1. Ver cartelera
2. Infomacion de reservas
3. Historial de compras
4. Salir


Si selecciona la opcion 1:

Bot: Usted selecciono ver la cartelera
Bot: Seleccione una pelicula:
1. Spiderman
2. Batman
3. Star Wars
4. Sing 2
5. Salir


Si selecciona una pelicula:

Bot: Usted Selecciono Batman
Seleccione un horario:

1. 13:00 - 15:30
2. 14:00 - 16:30 Sub
3. 15:00 - 17:30
4. Salir

Si selecciona un horario:

Bot: Numero de asientos?
(En caso de equivocacion presione 0 para retroceder)



Una vez seleccionado el numero de asientos el bot
procede a reealizar la venta de los tickets

Bot: Total de su compra ..... Bs
1. Pagar
2. Cancelar


Si selecciona 1

Bot: Ingrese datos de su tarjeta
(En caso de equivocacion presione 0 para retroceder)

Numero de tarjeta...
Fecha de expiracion...
Codigo de tres digitos...
Titular ded la tarjeta...

Una vez ingresados los datos

Bot: Pago acceptado / Pago denegado

Si pago aceptado

Bot: Codigo de ticket abc123

Si pago denegado

Bot: Hubo un problema con el metodo de pago

1. Reintentar
2. Salir


