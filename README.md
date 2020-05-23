# CursoDeExpresionesRegulares
https://platzi.com/clases/1301-expresiones-regulares/11847-que-son-las-expresiones-regulares/Curso de Expresiones Regulares

/*El lenguaje: caracteres, operadores, y construcciones*/

  /*El Caracter*/
    "." :=> El Caracter
  /*El Caracter*/

  /*Las clases predefinidas y construídas*/
    "." :=> Digito, Palabra, cualquier caracter y los espacios.
    \d :=> Solo los Digítos. =:> [0-9]
    \w :=> Todo lo que pueda ser parte de una palabra(Digitos, [a-zA-Z0-9_]) =:>[a-z] =:>[a-zA-Z0-9_]
    \s :=> Espacios
    \. :=> Para escapar y referirse al caracter ejm.
    * greedy :=> all
    + :=> Uno o más
  /*Las clases predefinidas y construídas*/
/*El lenguaje: caracteres, operadores, y construcciones*/

/*Ejemplos*/
  ^\w{2,2}[\-\. W]{0,1}\d{2,2}[\-\. W]{0,1}\d{2,2}$ =:> Busca números telefonicos.
  ^\[.*\[WARN\].*Error capturado en.*$ Busqueda en logs.
  https?:\/\/[\w\-\.]+\.\w{2,5}\/?.*\S$ Busqueda de URL
  [\w\._]{5,30}\+?[\w]{0,10}@[\w\.\-]{3,}\.\w{2,5}$ Mail
/*Ejemplos*/
