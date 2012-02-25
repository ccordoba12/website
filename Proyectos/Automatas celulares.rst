.. -*- mode: rst; mode: flyspell; mode: auto-fill; mode: wiki-nav-*- 

==========================================================
Simulación de autómatas celulares con vecindad de Margolus
==========================================================

.. raw:: html

   <table border="0" id="front-page" align="center">
   <td width="80%">

La parte más interesante y extensa de mi tesis de pregrado fue la creación de
un notebook en el que explicaba paso a paso cómo simular el flujo de arena por
un embudo, por medio de un autómata celular con vecindad de Margolus.

.. imagen del flujo por el embudo

Haciendo uso de las increíbles capacidades de manipulación simbólica que ofrece
*Mathematica*, ideé una forma en la que se podían definir gráficamente las
reglas de evolución del autómata y cree una paleta de para introducirlas
fácilmente al notebook.

.. imagen regla gráfica

Mi intención era que los futuros usuarios del notebook pudieran definir sus
propias reglas, sin tener que preocuparse por como programarlas, y que sólo
tuvieran que crear una rutina de visualización para observar los resultados de
sus autómatas. Como ejemplo, yo mismo definí las reglas del `gas HPP`_ y mostré
como éste puede reproducir cualitativamente el comportamiento de una onda de
presión en un gas de partículas.

.. imagen Margolus

Los interesados pueden descargar el :download:`notebook <../downloads/Automatas
celulares con vecindad de Margolus.zip>` (actualizado para Mathematica 8) y
encontrar más reglas de evolución para otros fenómenos físicos en la `tesis`_
de Norm Margolus.

.. _gas HPP: http://en.wikipedia.org/wiki/Lattice_gas_automaton

.. _tesis: http://people.csail.mit.edu/nhm/thesis.pdf

.. raw:: html
   </td>
   
   <td width="30%">
   <a href=../Proyectos/Mathematica.html>
   <img src="../_static/mathematica-4.png">
   </a>
   </td>
   </table>

..  LocalWords:  LocalWords pregrado Margolus table tr td notebook Mathematica
..  LocalWords:  HPP html width Norm download downloads zip pdf
