.. _oas:community:

24. Research Community (O)
--------------------------
--------------------------

``datacite:relatedIdentifier``

Identifiers of the community for which the research product is of interest. 

.. note::

   These must be globally unique identifiers and must be expressed using the format: ``ihttp://openaire/community/community_name/sub_community_name/...``

15.1 type (M)
-------------------

The type of the related identifier is the new OpenAIRE type OpenAIRE

15.2 relation (M)
------------------

Since we are talking about a community, the relationship mast be set to the OpenAIRE value "IsRelevanTo"

**Example**

.. code-block:: xml
   :linenos:

   <relatedIdentifier relatedIdentifierType="OpenAIRE" relationType="IsRelevanTo">
   		http://openaire/community/DH-CH/PARTHENOS
   </relatedIdentifier>