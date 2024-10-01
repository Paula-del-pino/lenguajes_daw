<!-- HEADINGS -->

# Prática de Markdown
# my title 
## my title h2
### my title h3 
#### my title h4

Markdown es un lenguaje de marcado ligero creado por **John Gruber** y Aaron Swartz que trata de conseguir *la máxima legibilidad* y *facilidad de publicación* tanto en su forma de entrada como de salida, inspirándose en muchas convenciones existentes para marcar mensajes de correo electrónico usando texto plano.

## Listas
### Desordenada

<!-- Unordered list -->
* manzana
* piña
* fresa
* naranja
    * mandarina
    * pomelo

### Ordenada

<!-- Ordered list -->
1. manzana
2. piña
3. fresa
4.  naranja

## Enlace a una URL externa

[Chuleta Markdown](https://www.markdownguide.org/cheat-sheet/)

## Code Block
`console.log("HolaYo")`´
```javascript
package unidad01;

import java.util.Scanner;

public class HolaYo {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner scan = new Scanner (System.in);
		System.out.println("Introduce tu nombre");
		String nombre = scan.nextLine();
		System.out.println("Introduce tu año de nacimiento");
		int anioNacimiento = scan.nextInt();
		int edad = 2024 - anioNacimiento;
		System.out.println("Hola" + nombre +"! Tienes " + edad + "años");
		scan.close();
```
## Tabla

| Sintaxís | Descripción | Código |
| -------- | ----------- |--------|
| Encabezado | Título 1 | Título 2|
| Párrafo | Texto| Párrafo 
|Texto|Párrafo|Texto 

## Imagen

![visual studio codo logo](https://brandlogos.net/wp-content/uploads/2021/11/visual-studio-code-logo.png "Visual studio code logo")