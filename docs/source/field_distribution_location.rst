
.. _oas:distributionLocation:

13. Distribution location (R)
---------------------------
---------------------------

``datacite:alternateIdentifier``

URL of the web location from which the software can be directly downloaded 
When the distribution location is specified the alternateIdentifierType attribute must be set to the OpenAIRE term DistributionLocation

Do Not Confuse With
----------------------
* :ref:`oas:landingPage`

**Example**

.. code-block:: xml
   :linenos:

   <alternateIdentifier alternateIdentifierType = "DistributionLocation">
   		http://my_distribution_location.eu
   </alternateIdentifier>

