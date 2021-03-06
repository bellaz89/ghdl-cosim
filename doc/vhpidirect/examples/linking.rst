.. program:: ghdl
.. _COSIM:VHPIDIRECT:Examples:linking:

Linking
#######

:cosimtree:`bind <vhpidirect/linking/bind>`
*******************************************

Although GHDL's elaborate command can compile and link C sources, it is sometimes preferred or required to call a compiler explicitly with custom arguments. This is useful, e.g., when a simulation is to be embedded in the build of an existing C/C++ application.

This example is equivalent to :ref:`COSIM:VHPIDIRECT:Examples:wrapping:basic`, but it shows how to use :option:`--bind` and :option:`--list-link` instead of :option:`-e`. See :ref:`COSIM:VHPIDIRECT:Linking` for further details.

.. HINT::
  Objects generated by :option:`--bind` are created in the working directory. See :ref:`gccllvm-only-programs` and :ghdlsharp:`781`.
