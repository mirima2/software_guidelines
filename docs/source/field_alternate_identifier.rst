.. _datacite:alternateIdentifier:

11. Alternate identifier (O)
---------------------------
---------------------------

``datacite:alternateIdentifier``

An identifier or identifiers other than the primary Identifier applied to the resource being registered. This may be any alphanumeric string which is unique within its domain of issue. May be used for local identifiers. AlternateIdentifier should be used for another identifier of the same instance (same location, same file) (occurrences: 0-n).


11.1 alternateIdentifierType (M)
--------------------------------

The type of the AlternateIdentifier (occurrences: 1).

If AlternateIdentifier is used, alternateIdentifierType is mandatory. 

**Example**

.. code-block:: xml
   :linenos:

   <alternateIdentifier alternateIdentifierType="URL">
        http://my_alternate_identifier.eu
   </alternateIdentifier>
   
