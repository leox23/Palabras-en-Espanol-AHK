AutoCorrección Español ~ AHK (AutoHotkey)
=============

**Este script no fue creado por mi, fue desarrollado inicialmente por @Pinkfloydd y luego cierto apoyo de [@leox23 (mi persona)](https://github.com/leox23), hay [un viejo hilo en el foro de AutoHotKey donde tome la iniciativa](https://www.autohotkey.com/boards/viewtopic.php?t=26048), unimos autocorrecciones continuando con este script que habia comenzado @Pinkfloydd, hice un fork al finalizar. @Pinkfloydd luego de un tiempo desaparecio sin motivos, y elimino todas sus cuentas, y lo que quedo del script fue este fork en el que ahora estas.**

<hr>

### Este script de AutoCorrección de palabras en Español, apunta mucho al uso obligatorio de tildes en las palabras, el script de autocorreccion en inglés [Autocorrect.ahk](https://www.autohotkey.com/download/AutoCorrect.ahk) tambien esta incluido.

Para encontrar patrones de tildes obligatorias, usar este sitio web:

http://buscapalabras.com.ar/buscarpalabras.php

Ej. 1 -> Todas las palabras terminadas en:
- sión
- ción

Llevan siempre tilde. y de tal manera, así (en parte) buscando y agregando más patrones.

Ej. 2 -> Sabemos que las palabras Limón y Timón siempre llevan tilde. Entonces nos suponemos que el patrón siempre terminado en imón lo tiene. Por lo tanto vamos a esa página a comprobarlo y colocamos "imon" (sin tilde)

De tal manera si es que no encuentra palabras terminadas en imon, significa que todos estos casos de palabras que la contengan, siempre cuentan con tilde.

Es decir, agregaríamos al Script:

- :?:imon::imón

[Mirar las últimas líneas de AutoCorrección.ahk](https://github.com/leox23/Palabras-en-Espanol-AHK/blob/332aad574add72109c02de5b484c873033f99b92/AutoCorrecci%C3%B3n#L4974), anteriores a la sección de Inglés.

--------------------------------------------------

Siéntase libre de contribuir al repositorio.

Contacto
-------
@leox23 (AHK Forums)

~~@Pink_floyd (T!)~~

~~@Pinkfloydd (AHK Forums)~~

~~@Pinkfloydd (GitHub)~~
