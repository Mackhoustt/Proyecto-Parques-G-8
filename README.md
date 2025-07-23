# Proyecto-Parques-G-8
Proyecto final para la materia de Programación para computadores 2025-01 Grupo 18.

Proyecto: Parqués UN para programadores

Integrantes: Mackling Javier Moreno Meléndez
             Maria José Garcia Castañeda
             
Descripción del juego

El presente proyecto consiste en el desarrollo de una implantación del clásico juego de mesa parqués/parchís en el leguaje de programación Python, jugable desde consola con una visualización del estado del tablero y sus elementos.

El juego se ciñe a las reglas originales, incluyendo movimientos de fichas, casillas seguras, capturas y turnos, asignando los valores mediante lanzamiento de los dados. El programa le permite al usuario elegir entre dos modalidades de juego: Modo real, en el cual se generan aleatoriamente dos valores del 1 al 6 o el Modo desarrollador en el cual el usuario puede ingresar los valores que tomaran cada uno de los dados. 

## Reglas de juego

Salida de la cárcel

* Una ficha saldrá de la cárcel si al lanzar los dados obtiene un 5 (ya sea en un dado o la suma de ambos) 
Casilla de salida 
* En la casilla de salida se podrán ubicar máximo  2 fichas. Si ya se encuentra ocupada por fichas de equipos contrarios no podrá sacar otra ficha hasta que se libere el espacio. En caso de que una de las dos fichas pertenezca al equipo podrá sacar la ficha y enviar la del equipo oponente a la cárcel. 
## Prioridad
* Es obligatorio sacar una ficha de la cárcel cuando sea posible, de lo contrario se omitirá el turno.
Casillas seguras
* En estas casillas especiales, no es posible capturar rivales. 
## Bloqueos
* Si dos fichas del mismo equipo se encuentran en una misma casilla, forman un bloqueo. Debido a esto ninguna ficha rival podrá pasar u ocupar está casilla.
  ## Capturas
* Si una ficha en una casilla no segura donde ya se encuentra una ficha rival, esta es capturada y enviada a su cárcel.
* El equipo que captura recibe 20 movimientos adicionales.
## Meta
* Una ficha llega a la meta solo con un número exacto de movimientos.
* Al alcanzar la meta con alguna de sus fichas, el equipo recibe 10 movimientos adicionales.
## Dados dobles
* Al obtener dados dobles el equipo repite turno.

Si obtienen tres pares consecutivos, la ultima ficha en ser movida por el equipo regresa a la cárcel. 
## Movimientos adicionales
* Los movimientos adicionales otorgados deben usarse inmediatamente antes de pasar el turno.
### No hay movimientos posibles
* Si no hay movimientos posibles, el turno es omitido y pasa al siguiente equipo.
## Victoria
  * El primer equipo que logre llevar todas sus fichas a la meta alcanza la victoria.
### Instrucciones

Nota: Para correr el programa su interprete debe contar con Python 3.x.
### Inicie el programa

## Seleccione la modalidad de juego que prefiera.

Ingrese el orden de turnos atendiendo al ejemplo dado en pantalla.

Siga las instrucciones impresas en consola para el lanzamiento de los dados y la elección del movimiento de fichas.
