AutoCorrección Español ~ AHK (AutoHotkey)
=============

AutoCorrección de palabras en Español, donde se apunta más que nada al uso obligatorio de tildes en las palabras.

--------------------------------------------------

Para encontrar patrones de Tildes obligatorias, usar esta página:

http://buscapalabras.com.ar/buscarpalabras.php

Ej -> Todas las palabras terminadas en:
- sión
- ción

Llevan siempre tilde. y de tal manera, así (en parte) buscando y agregando más patrones.

Ej 2 -> Sabemos que las palabras Limón y Timón siempre llevan tilde. Entonces nos suponemos que el patrón siempre terminado en imón lo tiene. Por lo tanto vamos a esa página a comprobarlo y colocamos "imon" (sin tilde)

De tal manera si es que no encuentra palabras terminadas en imon, significa que todos estos casos de palabras que la contengan, siempre cuentan con tilde.

Por lo tanto agregaríamos al Script:

- :?:imon::imón

[ Mirar las últimas líneas de AutoCorrección.ahk (anteriores a la sección de Inglés) ]

--------------------------------------------------

Sentirse libre de contribuir con el repositorio.

Muchas gracias.

Contacto
-------
@Pink_floyd (T!)

@Pinkfloydd (AHK Forums)

@Pinkfloydd (GitHub)
