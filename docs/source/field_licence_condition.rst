.. include:: ../common/replacements.rst

.. _oas:licenseCondition:

19. Licence Condition (MA)
---------------
---------------

``datacite:rights``
The Licence information for this resource.

**Allowed values, examples, other constraints**

Free text.


Use the complete title of a license and include version information if applicable.

Example: Creative Commons Attribution 3.0 Germany License

.. note::

   *Mandatory* property in OpenAIRE instead of optional in DataCite.

   OpenAIRE uses this property to explicit declare the licence of the resource via :ref:`d:rightsuri`. OpenAIRE recommends including license information if available.

  

.. _d:rightsuri:

19.1 rightsURI (M)
-------------------

The URI of the license (occurrences: 0-1).

**Allowed values, examples, other constraints**

Example:

http://creativecommons.org/licenses/by/3.0/de/deed.en

.. note::

   *Mandatory when applicable* property in OpenAIRE instead of optional in DataCite.


**Examples**

.. code-block:: xml
   :linenos:
   
   <rights rightsURI=”http://creativecommons.org/licenses/by/4.0/”>
       Creative Commons Attribution 4.0 International
   </rights>
   
