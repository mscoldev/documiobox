Usage
=====
Instalacion
____________

.. _instalacion2:

Esta es la tematica de la primera instalacion

.. _Instalacion:

Esta es la tematica de la segunda instalacion.

.. _installation:

Installation
------------

To use Lumache, first install it using pip:

.. code-block:: console

   (.venv) $ pip install lumache

Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

.. _Encabezado:

Este es el texto correspondiente a un encabezado.

.. _Text 2:

Este es el tema 2 correspondiente a este tipo de editor.

