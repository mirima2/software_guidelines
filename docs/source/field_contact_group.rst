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

The email of the contact group.


3.3 givenName (R)
-----------------

The name of the group.


3.4 affiliation (O)
-------------------

The organizational or institutional affiliation of the contributor.


**Usage Instruction**

This element is used for providing information about the contact group for the software. The contributorType must be set to the datacite term "ContactGroup". The contributor name must be set to a valid email for the contact group. The group name can be specified in the field givenName

**Example**

.. code-block:: xml
   :linenos:

   <contributor contributorType="ContactGroup">
     <contributorName>dnet-team@foo.com</contributorName>
     <givenName>DNet Team</givenName>
   </contributor>

   
