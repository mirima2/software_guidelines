.. _oas:relation:

15. RelatedIdentifier (O)
--------------------------
--------------------------

``datacite:relatedIdentifier``

Identifiers of related resources. These must be globally unique identifiers .

15.1 type (M)
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
* ``IGSN``
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


15.2 relation (M)
------------------

Description of the relationship of the resource being registered (A) and the related resource (B)



*Controlled List Values:*

* ``IsCitedBy`` (indicates that B includes A in a citation)
* ``IsSupplementTo`` (indicates that A is a supplement to B)
* ``IsSupplementedBy`` (indicates that B is a supplement to A)
* ``IsMetadataFor`` (indicates additional metadata A for a resource B)
* ``IsNewVersionOf`` (indicates A is a new edition of B, where the new edition has been modified or updated)
* ``IsVersionOf`` (indicates that A is a version of B)
* ``IsPreviousVersionOf`` (indicates A is a previous edition of B)
* ``IsPartOf`` (indicates A is a portion of B;may be used for elements of a series)
* ``HasPart`` (indicates A includes the part B)
* ``IsReferencedBy`` (indicates A is used as a source of information by B)
* ``References`` (indicates B is used as a source of information for A)
* ``IsDocumentedBy`` (indicates B is documentation about/explaining A)
* ``Documents`` (indicates A is documentation about/explaining B)

.. note::

   ``Cites`` and ``IsCitedBy`` is specifically for when one resource directly cites another resource in its references, whereas ``References`` and ``IsReferencedBy`` is for when a resource is used  without a direct citation. 

.. note::
	``IsDocumentedBy`` must be used with :ref:`oas:documentation`

**Example**

.. code-block:: xml
   :linenos:

   <relatedIdentifier relatedIdentifierType="DOI" relationType="IsCitedBy">10.110/...</relatedIdentifier>