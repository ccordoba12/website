.. -*- mode: rst; mode: flyspell; mode: auto-fill; mode: wiki-nav-*- 

====================================
Mejoras de resaltado a los notebooks
====================================

.. raw:: html

   <table border="0" id="front-page" align="center">
   <tr>
   <td width="80%"><img src="../_static/highlighting.png" id="highlighting"></td>
   <td width="30%" rowspan="2"><img src="../_static/mathematica-4.png"></td>
   </tr>
   <tr>
   <td>

Este proyecto nació en el 2003, cuando la versión actual de *Mathematica* era
la 4.2. En esa época estaba enseñándoles el programa a dos primitos muy
inteligentes, que aún estaban en el colegio. Mientras lo hacía, noté que la
falta de resaltado para el código que escribían en el notebook les dificultaba
mucho el aprendizaje del lenguaje [#]_.

En busca de soluciones encontré el código de `Luc Barthelet`_ que agregaba
algunas opciones de resaltado a través de un botón llamado *Beatiful*. Con base
en él, diseñé un paquete y un conjunto de botones que permitían resaltar
a todo un notebook y que añadían más posibilidades de resaltado,
además de un atajo de teclado para reaplicarlo continuamente. El problema era
que el resaltado no se podía aplicar en tiempo real, ya que sólo se hacía
modificando el color y estilo del texto que definía el código, así que cuando
el usuario escribía nuevo código, el resaltado usualmente se estropeaba y se
hacía necesario arreglarlo.

Los resultados fueron muy buenos y aún considero que el paquete es muy útil
para publicar notebooks en la web, por lo que lo he ido actualizando para que
funcione con cada nueva versión de *Mathematica* desde entonces.

.. [#] Este aspecto ha sido mejorado bastante desde la versión 6.

.. raw:: html
   
   </td>
   </tr>
   </table>

.. _Luc Barthelet:
   http://groups.google.com.co/group/comp.soft-sys.math.mathematica/browse_thread/
   thread/377a9eb137198e05/41daa2a212e360e9?q=Luc+Barthelet+beautiful&rnum=1&hl=
   es#41daa2a212e360e9



..  LocalWords:  notebooks LocalWords Mathematica notebook Luc Barthelet tr td
..  LocalWords:  Beatiful width img src static projects png html table rowspan
..  LocalWords:  mathematica highlighting
