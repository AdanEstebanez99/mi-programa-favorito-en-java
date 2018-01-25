# mi-programa-favorito-en-java
El programa que más me ha gustado de todos en Java

## La Piramide

La piramide es mi programa favorito en java por que fue el primer programa de dibujos que hicimos con bucles, y ademas fue el primer programa realmente complicado en comparació.n con los programas anteriores a este que eran mucho más simples.

A continuacion se muestra el codigo de *"La Piramide"* en java:

```java
/**
 * Ejercicio 19: Programa que pinta una piramide y tienes que introducirle
 * la altura y los caracteres.
 * 
 * @author Adán
 */

public class Piramide { // Clase principal
public static void main(String[] args) {
  System.out.println("Introduce la altura de la piramide:");
  int alturaIntroducida= Integer.parseInt( System.console().readLine());
  System.out.println("Introduce el caracter con el que quieres pintar la piramide:");
  String pintar = System.console().readLine();
  
  int altura = 1;
  int espacio = alturaIntroducida - 1;
  
  while (altura <= alturaIntroducida){
    
    for (int i = 1; i <= espacio; i++) {
      System.out.print(" ");
   }
    
    for (int i = 1 ; i <= (altura * 2) - 1; i++) {
      System.out.print(pintar);
  
  }
  System.out.println();
  altura++;
  espacio--;
  }
 }
 }

```

Para compilar el programa teclea lo siguiente:
```console
javac Piramide.java
```
## Resultado del Programa:

<img src="imagenes/Captura.jpeg">
