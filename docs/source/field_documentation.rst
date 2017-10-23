
.. _oas:documentation:

14. Documentation (R)
====================

``datacite:relatedIdentifier``

A resource intended for end-users providing useful information regarding the componet usage/application, e.g. execution tips, faq's, help forums etc.

14.1 type (M)
-------------------

The type of the related identifier

*Controlled List Values:*

* ``ARK``
* ``arXiv``
* ``bibcode``
* ``DOI``
* ``EAN13``
* ``EISSN``
* ``Handle``
* ``ISBN``
* ``ISSN``
* ``ISTC``
* ``LISSN``
* ``LSID``
* ``PMID``
* ``PURL``
* ``UPC``
* ``URL``
* ``URN``

14.2 relation (M)
------------------

The relation that binds the software and the provided documentation. When the documentation element is provided the relationType attribute must be set to the DataCite term IsDocumentedBy


**Example**

.. code-block:: xml
   :linenos:

   <relatedIdentifier relatedIdentifierType="URL" relationType="IsDocumentedBy">
     http://my_documentation.eu
   </relatedIdentifier>