# Ejercicio 1

El fragmento de código de nuestro fichero `test.js` nos devuelve un output no 
deseado. Queremos imprimir un valor incremental a cada segundo pero lo que 
nos devuelve el código es el mismo valor en cada iteración. 

1. Sin necesidad de ejecutar el código, ¿sabrías decirnos qué valor imprimiría
 por consola el script? 
    si, El resultado es 5
 ¿Cuál es el motivo?
    El setTimeout, ya que el ciclo se esta ejecutando normal, mietras el console debe de esperarse el tiempo asignado (1000) para poder mostrar el console.
2. Sabiendo que el output que buscamos es el que encuentras bajo estas líneas… 
¿Cómo solucionarías el fragmento de código para que el output sea el deseado?
    Respuesta 1:
        Si no se requiere ejecutar otra accion durante el la ejecucion del for, entonces se elimina el SetTimeout y asi se obtendra el resultado esperado.
    Respuesta 2:
        Si se requiere ejecutar otra funcion a parte del for, entonces el console se debe de colocar afuera del setTimeout, con esto mostrara los datos esperados sin afectar el stTimeou.

```
    > 0
    > 1
    > 2
    > 3
    > 4
```