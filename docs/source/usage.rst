Usage
=====

.. _installation:

Installation
------------

This repo is free-install. To use zju_wander, first git clone it into your local file:

.. code-block:: console

   (.venv) $ git clone https://github.com/ZhangJiahaoZJU/zju_wander.git

Preparation
----------------

1. Go to the '/software' file, and find the 'zju_wander.exe' software:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

