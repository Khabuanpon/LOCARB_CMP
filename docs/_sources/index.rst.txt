.. Carbon Footprint Organization documentation master file, created by
   sphinx-quickstart on Mon Nov 22 15:43:43 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

**Flimate Carbon Management Platform**
=========================================================
**Carbon Footprint for Organization** (CFO) is a type of method for visualizing the amount of greenhouse gas emissions from an organization's operations. which will lead to the determination of management guidelines and manage to reduce greenhouse gas emissions effectively both at the factory level industrial level and national level. Choosing emission factors is one of the most important part for CFO calculating. It pulls data from the `TGO Emission Factor
<http://thaicarbonlabel.tgo.or.th/admin/uploadfiles/emission/ts_578cd2cb78.pdf/>`_

**GHGs Calculation**
========================================================
**Outputs**

Y	=     Total GHG emission of Organization
 
Sc\ :sub:`i,j`\     =     GHG emission of scope `j`

y\ :sub:`i,j`\	=	GHG emission of activity by source `i` scope `j`

**Inputs**

x\ :sub:`i,j`\	=	Quantity of activity by source `i` scope `j`

EF\ :sub:`i,j`\	=	Emission factor of source `i` scope `j`

**Cost function**

.. math:: Y = \sum(Sc)
.. math:: Sc = \sum(y)
.. math:: y = \sum((x)(EF))

**Scj (Scope of Emission)**

Sc\ :sub:`1`\	=	 y\ :sub:`j(:41)`\

Sc\ :sub:`1s`\	=	 y\ :sub:`j(:42:48)`\

Sc\ :sub:`2`\	= 	y\ :sub:`j(:49)`\

Sc\ :sub:`3`\	= 	y\ :sub:`j(:50)`\


.. note::

  
.. toctree::
   :maxdepth: 2
   :caption: Contents:
  

**Description**
========================================================
.. csv-table:: **Source (Abbreviation and Description)**
   :file: D:\Work\Carbon Footprint\Platform\Description.csv
   :widths: 30, 40, 100
   :header-rows: 1

**Emission Factor**
========================================================
Scope 1 (Direct GHG Emissions)
========================================================
.. csv-table:: **Source and Emission Factor for Scope1**
   :file: D:\Work\Carbon Footprint\Platform\Scope1EF.csv
   :widths: 10, 20, 20, 20, 20
   :header-rows: 1

Scope 2 (Electricity indirect GHG emissions)
========================================================
.. csv-table:: **Source and Emission Factor for Scope2**
   :file: D:\Work\Carbon Footprint\Platform\Scope2EF.csv
   :widths: 10, 20, 20, 20, 20
   :header-rows: 1

Scope 3 (Other indirect GHG emissions)
========================================================
.. csv-table:: **Source and Emission Factor for Scope3**
   :file: D:\Work\Carbon Footprint\Platform\Scope3EF.csv
   :widths: 10, 20, 20, 20, 20
   :header-rows: 1

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
