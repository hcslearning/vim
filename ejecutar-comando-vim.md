Ejecución de Comandos en VIM
=============================

Para ejecutar un comando en Vim, basta con seguir una de estas alternativas:
1) :!comando %
Donde % es el nombre del archivo sobre el que estamos trabajando. Por ejemplo, el comando :!echo %, retornara miarchivo.tex.
2) :sh o :shell
Donde saldremos por un momento del programa y tendremos una shell completa para nosotros, podemos retornar a Vim presionando Ctrl+D para salir de la shell.


Otras tareas similares
========================

Para recuperar texto de otro o información sobre la ejecución de un comando, ocupamos el comando r. Los siguientes ejemplos muestran su uso:
1) :r textfile
Trae el texto completo del archivo 'textfile' hacia nuestro documento.
2) :r ! ls
Trae el texto que retorna el comando 'ls' hacia nuestro documento.
