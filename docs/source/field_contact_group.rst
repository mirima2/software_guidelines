.. _oas:contactGroup:

4. Contact Group (O)
====================

``datacite:contributor``

Information on the group responsible for providing further information regarding the resource

3.1 type (M)
-------------------


The type of the contributor (occurrences: 1). 

3.2 contributorName (M)
-------------------

The name of the contact group.


3.3 nameIdentifier (R)
----------------------

Uniquely identifies an individual or legal entity, according to various schemes.


3.3.1 nameIdentifierScheme (R)
------------------------------

The name of the name identifier scheme.


3.3.2 schemeURI (O)
------------------------------

The URI of the name identifier scheme.


3.3.3 affiliation (O)
-------------------

The organizational or institutional affiliation of the contributor.


**Usage Instruction**

This element is used for providing information about the contact group for the software. The contributorType must be set to the datacite term "ContactGroup".  The group name can be specified in the field givenName

**Example**

.. code-block:: xml
   :linenos:

   <contributor contributorType="ContactGroup">
     <contributorName>DNet Team</contributorName>
   </contributor>

   
