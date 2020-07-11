.. GRID documentation master file, created by
   sphinx-quickstart on Thu Jul  9 14:34:18 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

GRID: Deal with Field Segmentations Elegantly
==========================================================

Core features
--------------


Getting started
----------------

* **Installation**: 
  :ref:`Python 3` |
  :ref:`Dependencies` |
  :ref:`PyPI` |
  
* **First-time users**:
  :ref:`Demo mode` |
  :ref:`Work with your images <Work on your images>` |

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: GATTING STARTED

   /ch1_started/installation
   /ch1_started/firsttime

Interface
---------

* **File loading**:
  :ref:`Inputs` |
  :ref:`Drag and drop`

* **Area of interest**:
  :ref:`Define AOI` |
  :ref:`Adjust AOI`

* **K-means clustering**:
  :ref:`Clustering` |
  :ref:`Binarization` |
  :ref:`Refine clustering` |
  :ref:`Display/Zoom` |
  :ref:`Rotate images`

* **Centroids searching**:
  :ref:`Major axis` |
  :ref:`Minor axis` |
  :ref:`Switch between axes` |
  :ref:`Move/add/delete centroids`

* **Segmentation**:
  :ref:`Dynamic` |
  :ref:`Fixed` |
  :ref:`Fine-tune results` |
  :ref:`Reset` |
  :ref:`Display` |
  :ref:`Export results` |

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: INTERFACE

   /ch2_interface/load
   /ch2_interface/aoi
   /ch2_interface/kmeans
   /ch2_interface/centroids
   /ch2_interface/segmentation

Inputs/Outputs
--------------

* **Inputs**:
  :ref:`Images` |
  :ref:`Maps` |
  :ref:`Shape files`

* **Outputs**:
  :ref:`Tabular results` |
  :ref:`Images for validations` |
  :ref:`Shape files` |
  :ref:`NumPy form of AOI` |
  :ref:`H5 dataset`

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: INPUTS/OUTPUTS

   /ch3_io/inputs
   /ch3_io/outputs

Advanced usages
-----------------

* **Images from multiple seasons**:
  :ref:`Run GRID for the 1st season` |
  :ref:`Apply shapefiles to another season` |
  :ref:`Compare different seasons`

* **Work with QGIS**:
  :ref:`Obtain shapefiles from GRID` |
  :ref:`Load shapefiles to QGIS`

* **Customize vegetation indices**:
  :ref:`Obtain tabular outputs` |
  :ref:`Derive indices` |
  :ref:`Visualize indices`

* **Adapt to an arbitrary field layout**:
  :ref:`What's an arbitrary layout` |
  :ref:`Define centroids in GRID` |
  :ref:`Intepretate results`

* **Generate datasets for deep learning**:
  :ref:`Obtain h5 datasets` |
  :ref:`Process h5 files` |
  :ref:`Construct a DL model` |
  :ref:`Train & Evaluate`


.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: ADVANCED USAGES

   /ch4_adv/seasons
   /ch4_adv/qgis
   /ch4_adv/indices
   /ch4_adv/arbitrary
   /ch4_adv/dl

Citation
-------------------
To cite GRID, import the following BibTeX into reference managers:

.. code-block:: none

   @article{Chen and Zhang:2020,
    author       = {Chunpeng James Chen and Zhiwu Zhang},
    title        = {GRID: A Python Package for Field Plot Phenotyping Using Aerial Images},
    month        = may,
    year         = 2020,
    journal      = {Remote Sensing},
    volume       = 12,
    issue        = 11,
    pages        = 1697
    doi          = {10.3390/rs12111697},
    url          = {https://doi.org/10.3390/rs12111697}
   }

or add the bibliography directly:

.. code-block:: none

    Chen, C.J.; Zhang, Z. GRID: A Python Package for Field Plot Phenotyping Using Aerial Images. Remote Sensing 2020, 12, 1697, doi:10.3390/rs12111697.

