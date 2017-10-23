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
* ``Cites`` (indicates that A includes B in a citation)
* ``IsSupplementTo`` (indicates that A is a supplement to B)
* ``IsSupplementedBy`` (indicates that B is a supplement to A)
* ``IsContinuedBy`` (indicates A is continued by the work B)
* ``Continues`` (indicates A is a continuation of the work B)
* ``HasMetadata`` (indicates resource A has additional metadata B)
* ``IsMetadataFor`` (indicates additional metadata A for a resource B)
* ``IsNewVersionOf`` (indicates A is a new edition of B, where the new edition has been modified or updated)
* ``IsPreviousVersionOf`` (indicates A is a previous edition of B)
* ``IsPartOf`` (indicates A is a portion of B;may be used for elements of a series)
* ``HasPart`` (indicates A includes the part B)
* ``IsReferencedBy`` (indicates A is used as a source of information by B)
* ``References`` (indicates B is used as a source of information for A)
* ``IsDocumentedBy`` (indicates B is documentation about/explaining A)
* ``Documents`` (indicates A is documentation about/explaining B)
* ``isCompiledBy`` (indicates B is used to compile or create A)
* ``Compiles`` (indicates B is the result of a compile or creation event using A)
* ``IsVariantFormOf`` (indicates A is a variant or different form of B, e.g. calculated or calibrated form or different packaging)
* ``IsOriginalFormOf`` (indicates A is the original form of B)
* ``IsIdenticalTo`` (indicates that A is identical to B, for use when there is a need to register two separate instances of the same resource)
* ``IsReviewedBy`` (indicates that A is reviewed by B)
* ``Reviews`` (indicates that A is a review of B)
* ``IsDerivedFrom`` (indicates B is a source upon which A is based)
* ``IsSourceOf`` (indicates A is a source upon which B is based)

.. note::

   ``Cites`` and ``IsCitedBy`` is specifically for when one resource directly cites another resource in its references, whereas ``References`` and ``IsReferencedBy`` is for when a resource is used  without a direct citation.

.. note::
	``IsDocumentedBy`` must be used with :ref:`oas:documentation`

**Example**

.. code-block:: xml
   :linenos:

   <relatedIdentifier relatedIdentifierType="DOI" relationType="IsCitedBy">10.110/...</relatedIdentifier>