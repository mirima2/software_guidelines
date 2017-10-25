.. include:: replacements.rst

.. _oas:accessRights:

18. Access Rights (M)
---------------
---------------

``datacite:rights``

Any rights information for this resource.

**Allowed values, examples, other constraints**

Free text.

Provide a rights management statement for the resource or reference a service providing such information. Include embargo information if applicable.


.. note::

   *Mandatory* property in OpenAIRE instead of optional in DataCite.

   OpenAIRE uses this property to explicit declare the access right of the resource via :ref:`d:rightsuri`. 


.. _d:rightsuri:

18.1 rightsURI (M)
-------------------
The URI of the license (occurrences: 0-1).

**Allowed values, examples, other constraints**


   Use terms from the `info:eu-repo-Access-Terms vocabulary <http://purl.org/eu-repo/semantics/#info-eu-repo-AccessRights>`_. The values are:

   * ``info:eu-repo/semantics/closedAccess``
   * ``info:eu-repo/semantics/embargoedAccess``
   * ``info:eu-repo/semantics/restrictedAccess``
   * ``info:eu-repo/semantics/openAccess``

   

.. note::

   *Mandatory when applicable* property in OpenAIRE instead of optional in DataCite.

   This property should not be used to explicitly declare the license for the resource, for this refer to section :ref:`oas:licenceCondition`.



**Examples**


.. code-block:: xml
   :linenos:

  
  <rights rightsURI=”info:eu-repo/semantics/openAccess”> Open </rights>
   

  <rights rightsURI=”info:eu-repo/semantics/openAccess” />

