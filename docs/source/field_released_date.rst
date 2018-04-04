.. _oas:releaseDate:

9. Release date (R)
--------------------
--------------------
``datacite:date``

The release date of the software.

**Allowed values, examples, other constraints**

``YYYY``, ``YYYY-MM-DD``, ``YYYY-MM-DDThh:mm:ssTZD`` or any other format or level of granularity described in `W3CDTF <http://www.w3.org/TR/NOTE-datetime>`_. 


8.1 dateType (M)
----------------

The type of date (occurrences: 1).

If Date is used, dateType is mandatory, and its value must be set to the DataCite term Issued or to the DataCite term Available.


**Example**

.. code-block:: xml
   :linenos:

   <date dateType="Issued">23-10-2017</date>
