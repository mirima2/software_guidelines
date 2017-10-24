
.. _oas:fundingReference:

22. Funding Reference (R)
====================

``datacite:fundingReference``

Information about the funding entity that provided support to the development of the software.

22.1 Funder name (M)
-------------------

Name of the funder

22.2 Funder identifier (O)
-------------------

Identifier that univocally identifies the funder

22.2.1 Funder identifier type (O)
----------------------------------

**Allowed values, examples, other constraints**


   Can be assume one value from the following list:

   * ``ISNI``
   * ``GRID``
   * ``CrossRefFunder``
   * ``Other``



22.3 Award number (O)
-------------------

The grant ID assigned to the funder


22.3.1 Award URI (O)
-------------------

URI of the landing page associated to the funding


22.4 Award title (O)
-------------------

Title of the award


**Example**

.. code-block:: xml
   :linenos:

   <fundingReference>
   		<funderName>name of the number</funderName>
   		<funderIdentifier funderIdentifierType="ISNI">ISNI ID </funderIdentifier>
   		<awardNumber>award_number</awardNumber>
   		<awardTitle>
   			On the applications of the fastFourier transform 
   		</awardTitle>
   </findingReference>


   



