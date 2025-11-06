About Kevin
###########

.. figure:: _images/singe.jpg
   :alt: monkey of Mons
   :width: 150

.. contents:: Contents
   :local:

.. _ktp_quote:

Favorite Quote
---------------

   I don't know. I'm making this up as I go.

   -- Indiana Jones

.. _ktp_homes:

Places I've lived
-----------------

#. Virginia :sup:`3`
#. California :sup:`2`
#. Florida
#. Belgium
#. Oregon

.. _ktp_funwords:

Fun words
---------

proclivity
   a tendency to choose or do something regularly; an inclination or predisposition toward a particular thing.

fastidious
   very attentive to and concerned about accuracy and detail.

.. _ktp_links:

Links
-----

* `Intel <https://intel.com>`__
* `Kickstarter <http://kickstarter.com>`__
* `Places I've lived <#places-i-ve-lived>`__

More directives
----------------

.. warning:: What follows is more advanced!

Code blocks
............

This is how you display :code:`code` inline and in a block:

.. code-block:: python

   apples = 0
   oranges = 0
   other = 0
   for fruit in basket:
      if fruit.type == 'apple':
         apples += 1
      elif fruit.type = 'orange':
         oranges += 1
      else:
         other += 1

This is another code block showing the syntax of the table directive below:

.. code-block::

    .. list-table:: Desserts list table <- argument
       :header-rows: 1                  <- option

       * - Item                         <- content
         - Description
         - Price
       * - Cake
         - Suitable for weddings or birthdays.
         - $25

Tables
.......

.. list-table:: Desserts list table
   :header-rows: 1

   * - Item
     - Description
     - Price
   * - Cake
     - Suitable for weddings or birthdays.
     - $25
   * - Brownies
     - Great if you love chocolate.
     - $10
   * - Banana Split
     - An ice cream sundae between two halves of a banana.
     - $6