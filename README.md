# Operaciones con Matrices
## Descripcion general
Un proyecto en lenguaje ensamblador para sumar o restar 2 matrices.

El programa permite al usuario entrar las dimensiones de las matrices, entrar los elementos uno por uno de forma ordenada, elegir una de las 2 operaciones a realizar y luego muestra el resultado.

## Detalles de uso
### Para abrir e instalar el proyecto
Es necesaria la instalacion del programa Emu8086, una vez instalado puede ejecutar el proyecto abriendo el ejecutable Proyecto.exe_

### Instrucciones al usar el programa
Al abrir el programa, este solicitará la cantidad de columnas y filas que tendran ambas matrices(ambas matrices deben tener las mismas dimensiones para que la suma y la resta sea posible). Luego pedirá los elementos de la primera matriz y luego de la segunda. Luego le dara la operacion a elegir en forma de lista, a lo cual usted deberá elegir e introducir el caracter correspondiente a la operacion deseada.

### Reglas
- Todas las entradas al programa deben ser números naturales, positivos y menores que 256.
- El programa automaticamente pondrá los espacios y saltos de linea necesarios por cada valor
- Para entrar un numero solo debe escribir su valor con caracteres numéricos y luego presionar enter.

## Detalles de funcionamiento
- Para ver el codigo del proyecto abra el archivo Proyecto.exe.~asm con un editor de texto
- Para ver el uso de memoria al abrir al ejecutar el programa, abra el archivo Proyecto.exe.list con un editor de texto
- Tambien puede ver una tabla con las variables usadas en el programa en el archivo Proyecto.exe.Symbol
> La variable matriz es usada para marcar el inicio de las 2 matrices de entrada y la del modulo del resultado, las cuales se van alternando las posiciones de memoria desde el primer elemento de cada matriz hasta el ultimo elemento de cada matriz

 
