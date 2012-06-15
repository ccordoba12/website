.. -*- mode: rst; mode: flyspell; mode: auto-fill; mode: wiki-nav-*- 

==================================================
Mejoras de resaltado a los notebooks (2003 - 2004)
==================================================

.. raw:: html

   <table border="0" id="front-page" align="center">
   <tr>
   <td width="80%"><img src="../_static/highlighting.png" id="highlighting"></td>
   <td width="30%" rowspan="2">
   <a href=../Proyectos/Mathematica.html>
   <img src="../_static/mathematica-4.png"></td>
   </a>
   </tr>
   <tr>
   <td>

Este proyecto nació en el 2003, cuando la versión actual de *Mathematica* era
la 4.2. En esa época estaba enseñándoles el programa a dos primitos muy
inteligentes, que aún estaban en el colegio. Mientras lo hacía, noté que la
falta de resaltado para el código que escribían en el notebook les dificultaba
mucho el aprendizaje del lenguaje, aunque les parecía muy interesante el
entorno [#]_.

En busca de soluciones encontré el código de `Luc Barthelet`_, que agregaba
algunas opciones de resaltado a través de un botón llamado *Beatiful*. Con base
en él, diseñé un paquete y un conjunto de botones que permitían resaltar todo
un notebook y que añadían más posibilidades de resaltado que el botón de Luc,
junto con un atajo de teclado para reaplicarlo continuamente. Dado que no es
posible tener acceso al funcionamiento interno de *Mathematica*, no pude
encontrar ninguna forma de aplicar el resaltado en tiempo real. Lo que hace el
paquete es modificar el color y estilo del código en el notebook, así que
cuando el usuario escribe nuevos comandos y funciones sobre el código actual,
el resaltado usualmente se estropea y se hace necesario reaplicarlo.

Los resultados fueron muy buenos y aún considero que el paquete es muy útil
para publicar notebooks en la web, por lo que lo he ido actualizando para que
funcione con cada nueva versión de *Mathematica* desde entonces. El código
puede descargarse desde este :download:`link <../downloads/MathEditor.zip>` y
pueden seguirse los cambios que le voy realizando en su `repositorio`_ de
Bitbucket.

.. [#] Cabe anotar que este aspecto ha sido mejorado bastante desde la versión 6.

.. _Luc Barthelet:
   http://groups.google.com.co/group/comp.soft-sys.math.mathematica/browse_thread/
   thread/377a9eb137198e05/41daa2a212e360e9?q=Luc+Barthelet+beautiful&rnum=1&hl=
   es#41daa2a212e360e9

.. _repositorio: https://bitbucket.org/ccordoba12/matheditor/src/b37473503171/MathEditor

.. raw:: html
   
   </td>
   </tr>
   </table>


..  LocalWords:  notebooks LocalWords Mathematica notebook Luc Barthelet tr td
..  LocalWords:  Beatiful width img src static projects png html table rowspan
..  LocalWords:  mathematica highlighting Bitbucket link downloads MathEditor
..  LocalWords:  download zip
