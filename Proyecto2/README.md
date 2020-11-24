# Cálculo del índice de Cobertura Nubosa (CCI)

Programa en java (Java 14) que recibe una imagen en formato .jpeg y devuelve el índice de cobertura nubosa de la imagen (CCI).

### Entrada

La entrada del programa es el nombre de una imagen en formato jpeg de 4,368 píxeles de ancho y 2,912 píxeles de alto. La imagen del cielo se encuentra en un círculo de centro (2184,1456) y de radio aproximado de 1324 píxeles contenida en el rectángulo de cada imagen.

El programa recibe en la entrada estándar los archivos de imagen. Las siguientes entradas son válidas para el programa:

```
java -cp target/Proyecto-2.jar MyP.proyectoDos.Proyecto2 Nubes 11773.jpeg S
java -cp target/Proyecto-2.jar MyP.proyectoDos.Proyecto2 Nubes 11773.jpeg s
java -cp target/Proyecto-2.jar MyP.proyectoDos.Proyecto2 Nubes 11773.jpeg
```

Donde `Nubes 11773.jpeg` es la imagen.

## Bibliotecas utilizadas

Se usaron las bibliotecas de Java:

## Para compilar y correr el código

Para compilar el código debe escribirse:

```
mvn compile
```

Una vez compilado debe escribirse:

```
mvn install
```

Una vez instalado para ejecutar el código debe escribirse:

```
java -cp target/Proyecto-2.jar MyP.proyectoDos.Proyecto2 
```

## Para correr las pruebas

Para ejecutar las pruebas debe compilarse el proyecto haciendo.

```
mvn compile
```

Después escribir.

```
mvn test
```

Lo que ejecutará las pruebas del código.


