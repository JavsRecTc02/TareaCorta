# TareaCorta 1
### Historias de Usuario:
```markdown
◆ Como Desarrollador: Quiero crear una pantalla en la que puedo colocar los demás componentes del juego.

◆ Como Dessarrollador: quiero crear el panel con colores y que este se muestre en pantalla.

◆ Como Desarrollador: quiero implementar que sea visible el nivel en el que se encuentra el jugador.

◆ Como Desarrollador: quiero crear secuencias con los colores de una forma aleatoria.

◆Como Desarrollador: quiero que cada color del panel se ilumine cuando corresponda en la secuencia.

◆ Como Desarrollador: quiero lograr que cada vez que suba el nivel la secuencia aumente y sea mas rapida.

◆ Como Desarrollador: quiero comparar la secuencia dada aleatoriamente con la del jugador.

◆ Como Usuario: quiero poder ver el nivel de juego en el que me encuentro.

◆ Como Usuario: quiero que cada nivel vaya aumentando la dificultad del juego.

◆Como Usuario: quiero poder introducir mi secuencia dentro del juego.

◆Como Desarrollador: quiero lograr que si la secuencia del juegador es diferente a la del juego , este se reinicie.
```

## ➔Diseño
En la siguiente imagen se muestra el **diagrama de clases** realizado para la planeacion del juego , el cual contiene las clases y subclases

![Diagrama de Clases 1](https://raw.githubusercontent.com/JavsRecTc02/TareaCorta/gh-pages/SimonTec%20(1).png)

## ➔Clasificacion por criticidad y frecuencia
◆Se presenta un cuadro que compara features del programa SimonTec para ver de una forma mas clara el uso de estos.

◆Mas Usado____________________________________________________________________________________

           |Abrir ventana de juego|         | Mostrar color   |         |  Mostrar nivel  |
           |    Frecuencia alta   |         | Frecuencia alta |         | Frecuencia alta |
 
          ------------------------------------------------------------------------------------
           |  Seleccion de color  |         | Cambio dificultad |         |   Añadir color   |     
           |   Frecuencia media   |         | Frecuencia media  |         | Frecuencia media |
           
                         |  Aumentar el nivel   |                | Cambio de velocidad |             
                         |   Frecuencia media   |                |  Frecuencia media   |
                         
          ------------------------------------------------------------------------------------               
           |  Ganar el juego   |         | Perder el juego |             
           |  Frecuencia baja  |         | Frecuencia baja |      
          ___________________________________________________________________________________
◆Menos Usado

## ➔Minimal system span
```markdown
◆El minimal system span es un concepto que se refiere a las minimas funciones, clases o features que debe tener un programa para ser funcional.

◆En el caso de este juego serian los siguientes:

◆Feature que cree y abra la ventana del juego

◆Feature que establesca los componentes necesarios que deben mostrarse en pantalla

◆Feature que guarde la secuencia del juego y del usuario

◆Feature que compare ambas secuencias

◆Feature que aumente el nivel y la dificultad de este
```

## Editor:
```markdown
Javier Tenorio Cervantes
```

