.. _oas:community:

23. Community (O)
--------------------------
--------------------------

``datacite:relatedIdentifier``

Identifiers of the community for which the research product is of interest. 

.. note::

   These must be globally unique identifiers and must be expressed using the format: ``info:eu-repo/OAC/community_name/sub_community_name/...``

15.1 type (M)
-------------------

The type of the related identifier is the new OpenAIRE type OAC (OpenAIRE community)

15.2 relation (M)
------------------

Since we are talking about a community, the relationship mast be set to the OpenAIRE value "IsRelevanTo"

**Example**

.. code-block:: xml
   :linenos:

   <relatedIdentifier relatedIdentifierType="AOC" relationType="IsRelevanTo">
   		info:eu-repo/OAC/EGI
   </relatedIdentifier>