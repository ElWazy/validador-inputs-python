# Validador Inputs Python
Función que evita los errores de la funcion input, ademas de tener la falicidad de generar mensajes predefinidos
## Como usar la función.
1.- Abrir la consola y Ubicarse en el directorio (carpeta) del proyecto con: 
  - `dir` para windows o `ls` para saber que directorio estamos. 
  - `cd [NOMBRE_CARPETA]` para entrar a al directorio.
  - `cd ..` para salir del directorio.

2.- Clonar (descargar) el repo (proyecto) con:
```
git clone https://github.com/ElWazy/validador-inputs-python.git
```
3.- Importar el modulo, es recomendable importar al principio del codigo con:
```py
import validador
```
## Para que sirve el programa.
1.- Soluciona el ValueError.
  - Olvidate de que el programa explote cuando le pides al usuario un `int` y el maldito te escribe un `str`, con el validador nunca más!!

2.- Mensajes predefinidos.
  - Cansado de que escribir `Ingrese un numero:`, el validador trae mensajes predefinidos, que tú puedes modificar.
