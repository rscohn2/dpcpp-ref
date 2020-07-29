.. _oneapi-programming-model:

===================
 Programming Model
===================


DPC++ defines a parallel programming model for distributing a
computation across a :term:`host` and :term:`processing element`\s of a
heterogenous system. The parallel programming model is an extension of
Khronos* SYCL*. Every SYCL program is also a DPC++ program, but the
reverse is not true when an application uses DPC++ extensions.  The base 
language of DPC++ and SYCL is C++, with no extensions.  All DPC++
functionality is invoked via interfaces defined by a set of C++
classes, which are introduced in this section and described in detail
in :ref:`programming-interface`.

.. toctree::

   
   sample-program
   platform-model
   execution-model
   memory-model
   kernel-programming-model
   error-handling
   fall-back
