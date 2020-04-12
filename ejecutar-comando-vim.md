Ejecución de Comandos en VIM
=============================

Para ejecutar un comando en Vim, basta con seguir una de estas alternativas:

1) Donde % es el nombre del archivo sobre el que estamos trabajando. Por ejemplo, el comando :!echo %, retornara miarchivo.tex.
```
:!comando %
```

2) Donde saldremos por un momento del programa y tendremos una shell completa para nosotros, podemos retornar a VIM presionando Ctrl+D para salir de la shell.
```
:sh
# también puede ser 
:shell 
```


Otras tareas similares
========================

Para recuperar texto de otro o información sobre la ejecución de un comando, ocupamos el comando r. Los siguientes ejemplos muestran su uso:
1) Trae el texto completo del archivo 'textfile' hacia nuestro documento.
```
:r textfile 
```
2) Trae el texto que retorna el comando 'ls' hacia nuestro documento.
```
:r ! ls
```
