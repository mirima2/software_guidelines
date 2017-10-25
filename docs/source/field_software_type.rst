.. _oas:softwareType:

7. Software Type (M)
====================

``datacite:resourceType``

Specifies the type of the software being described. Free text.

7.1 type (M)
-------------------


**Usage Instruction**

This element contains information about the type of software. Since we are describing software resources, the resourceTypeGeneral must be set to the DataCite term "Software"

.. note::
  For OpenAIRE-Connect communities a controlled vocabulary established for each community must be used


**Example**

.. code-block:: xml
   :linenos:

   <resourceType resourceTypeGeneral="Software">
     	Python script
   </resourceType>

   
