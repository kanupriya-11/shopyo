======
Models
======

.. toctree::
    :titlesonly:


Creating a model
----------------

Here is a sample model which uses sqlalchemy


.. literalinclude:: ../shopyo/modules/contact/models.py
   :language: python
   :linenos:
   :lines: 5-26

🔩 Migrations
-------------

.. note::

   You can run

   .. code:: bash

       shopyo <command>

   or

   .. code:: bash

       python manage.py <command>

In case of change to models, do

.. code-block:: python
   :caption: Updating the database.
   :name: migrations

   python manage.py db migrate
   python manage.py db upgrade

