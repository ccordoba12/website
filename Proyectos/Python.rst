.. -*- mode: rst; mode: flyspell; mode: auto-fill; mode: wiki-nav-*- 

===================
Python (Desde 2009)
===================

.. raw:: html

   <table border="0" id="front-page" align="center">
   <td width="74%">

Mientras concluía mi maestría en el 2008, sentí la necesidad de contar con un
lenguaje sencillo y versátil, con el que pudiera analizar rápidamente los
resultados de las simulaciones que estaba realizando.

Debido al contacto con el movimiento *open source* que tuve durante mi tesis,
sabía que este lenguaje
no podía ser :doc:`Mathematica <Mathematica>`. La razón principal es que su
licencia es demasiado costosa para que pueda ser utilizado con facilidad por
estudiantes y profesores de universidades públicas en nuestro país. Además, la
comunidad que lo utiliza es pequeña y localizada, lo que dificulta el obtener
ayuda para resolver distintos tipos de problemas.

No me tomó mucho tiempo darme cuenta que el lenguaje que mejor se adaptaba a
mis requerimientos es
`Python`_. *Python* cuenta con un conjunto de librerías científicas estables
y bien desarrolladas (como `Numpy`_ y `SciPy`_), con una interfaz eficiente y
hecha a medida para el trabajo científico (`IPython`_), y con una comunidad
numerosa y amigable.

Otra de las grandes ventajas de *Python* --además de ser muy fácil de
aprender-- es que *no* está hecho por o para científicos, pues es un lenguaje
de `propósito general`_. Esto significa que ha sido diseñado para realizar
cualquier tipo de tarea, lo cual lo hace
más potente y flexible que un lenguaje especializado (que son en los que se
basan *Mathematica* o *Matlab*). Gracias a ello, ha sido
utilizado para crear gran cantidad de programas y librerías, casi podría
decirse que una para todo propósito imaginable! [#]_.

Debido a que *Mathematica* está basado en el paradigma de `programación
funcional`_, a mediados del 2009 decidí crear un paquete llamado :doc:`funckit
<funckit>`, que lo soportara de mejor manera en *Python* y que me permitiera a
mí, y quizá a otros en mi situación, hacer una transición más sencilla hacia
él.

Más adelante, durante la pŕimera mitad del 2010 estuve buscando
desesperadamente un ambiente integrado con el que me sintiera a gusto a la
hora de desarrollar programas científicos basados en *Python*. Después de probar
muchas alternativas, finalmente me decidí por :doc:`Spyder <Spyder>`, proyecto
con el que además he estado colaborando desde entonces, añadiéndole varias
características adicionales.

.. [#] Como puede verse en `PyPI <http://pypi.python.org/pypi>`_, el mayor
       repositorio de software libre del lenguaje.

.. _propósito general: http://en.wikipedia.org/wiki/General-purpose_programming_language
.. _Python: http://www.python.org/
.. _Numpy: http://numpy.scipy.org/
.. _SciPy: http://www.scipy.org/
.. _IPython: http://ipython.org/
.. _programación funcional: http://en.wikipedia.org/wiki/Functional_programming

.. raw:: html
   </td>
   
   <td width="40%">
   <img id="python-logo" src="../_static/python.png">
   </td>
   </table>

..  LocalWords:  Python open source Mathematica static python src logo png td
..  LocalWords:  html width table Numpy SciPy IPython PyPI funckit doc Spyder
..  LocalWords:  LocalWords
