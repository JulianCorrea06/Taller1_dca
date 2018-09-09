# Taller 1 DCA - Julián David Correa Gutiérrez

## Clase Main
### Esta clase presenta los métodos principales para la ejecución del programa

Metodos:
**settings()**
Controla el tamaño de la pantalla
**setup()**
Presenta las acciones que solo se ejecutan una vez
**draw()**
Se ejecuta varias veces para pintar las figuras en la interfaz
**mousePressed()**
Presenta las acciones cuando el un boton del mouse está siendo presionado
**mouseDragged()**
Presenta las acciones cuando el un boton del mouse está siendo presionado 
y el cursor se está moviendo
**mouseClicked()**
Presenta las acciones cuando se ha hecho click
**keyPressed()**
Presenta las acciones cuando se usa el teclado

## Clase Logica
### Esta clase presenta métodos que hacen referencia a la lógica principal del proyecto

Metodos:
**pintar()**
Se ejecuta varias veces para pintar las figuras en la interfaz
**mouse()**
Se ejecuta las veces que se interactúe con el mouse
**clickMan()**
Se ejecuta cuando se hace click es sostenido
**tecla()**
Se ejecuta cuando se hace uso de lsa teclas del teclado.

## Clase Etapa
### Esta clase presenta métodos que se utilizan para pasar de etapas en el programa.

Metodos:
**pintar()**
Se ejecuta varias veces para pintar las figuras en la interfaz
**sigEtapa()**
Se ejecuta para pasar de etapa y seguir con el programa

##Clase Rosa
### Clase en donde el usuario debe mantener presionado el click izquierdo sobre la rosa para pasar de etapa.

Metodos:
**pintar()**
Pinta la rosa y el planeta en el que esta plantada
**contar()**
Se ejecuta para contar los segundos en el que el click esta siendo presionado encima de la rosa

##Clase Planeta
### Clase en donde el usuario debe arrastrar unas esferas pequeñas a una esfera grande para pasar de etapa.

Metodos:
**pintar()**
Se ejecuta para pintar el planeta grande
**agregar(Bolita):boolean**
Se ejecuta para saber cuando se esta agregando una roca al planeta principal
**getBolitasRef()**
Se ejecuta para saber que rocas se han agregado al planeta principal

### Clase Bolita
#### Clase en donde se trata con las rocas pequeñas de la etapa de Planeta

Metodos:
**pintar()**
Se ejecuta para pintar las rocas pequeñas
**mover()**
Se ejecuta para mover las rocas pequeñas
**getX()**
Se ejecuta para obetener la coordenada X de cierta roca
**getY()**
Se ejecuta para obtener la coordenada Y de cierta roca

## Clase Luna
### Clase donde el usuario debe arrastrar la luna a cierto punto para poder pasar de etapa

Metodos:
**pintar()**
Se ejecuta para pintar la luna 
**arrastrar()**
Se ejecuta para mover la luna

## Clase Nave
### Clase donde el usuario debe presionar la tecla espacio para hacer a la nave despegar y pasar de etapa

Metodos:
**pintar()**
Se ejecuta para pintar la nave
**teclear()**
Se ejecuta para que cuando el usuario presione la barra espaciadora, la nave se mueva

## Clase Luces
### Clase donde el usuario debe presionar click derecho repetidas veces para crear estrellas pequeñas en el lienzo

Metodos:
**pintar()**
Se ejecuta para pintar una estrella cada vez que el usuario da click derecho
**click()**
Se ejecuta para saber cuando el usuario está dando click derecho en el lienzo

## Clase Sol
### Clase donde el usuario debe dar click en cierta parte del lienzo para generar nuevos colores en el sol de la composición y pasar de etapa
Metodos:
**pintar()**
Se ejecuta para pintar los nuevos colores del sol.
**click()**
Se ejecuta para reconocer cuando el usario está dando click izquierdo en la zona sensible del lienzo

## Clase Estrella
### Clase donde el usuario debe ir clickeando puntos apagados de una estrella para encenderlos en orden, una vez todo los puntos estén encendidos se pasa a la siguiente etapa
Metodos:
**pintar()**
Se ejecuta para pintar la estrella con los puntos apagados y encendidos
**click()**
Se ejecuta para reconocer cuando el usuario está dando click en una zona sensible activa

## Clase Espacio
### Clase en la que el usuario debe teclear la palabra "Space" para pasar de etapa

Metodos:
**pintar()**
Se ejecuta para pintar la palabra space en el lienzo.
**teclear()**
Se ejecuta para que el usuario este en la capacidad de escribir space con su teclado y pasar de etapa.




