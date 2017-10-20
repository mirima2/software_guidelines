.. _oas:contactPerson:

3. Contact Person (O)
====================

``datacite:contributor``

Information on the person responsible for providing further information regarding the resource

3.1 type (M)
-------------------


The type of the contributor (occurrences: 1). 

3.2 contributorName (M)
-------------------

The email of the contact person.


3.3 givenName (R)
-----------------

The personal or first name of the author.


3.4 familyName (R)
------------------

The surname or last name of the author.


3.5 nameIdentifier (R)
----------------------

Uniquely identifies an individual or legal entity, according to various schemes.


3.5.1 nameIdentifierScheme (R)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The name of the name identifier scheme.


3.5.2 schemeURI (O)
^^^^^^^^^^^^^^^^^^^

The URI of the name identifier scheme.


3.5.3 affiliation (O)
-------------------

The organizational or institutional affiliation of the contributor.


**Usage Instruction**

This element is used for providing information about the contact person for the software. The contributorType must be set to the datacite term "ContactPerson". The contributor name must be set to a valid email for the contact person. The information about the given name and family name for the contact person can be specified in the fields givenName and familyName

**Example**

.. code-block:: xml
   :linenos:

   <contributor contributorType="ContactPerson">
     <contributorName>pippo@foo.com</contributorName>
     <givenName>Name</givenName>
     <familyName>Surname</familyName>
   </contributor>

   
