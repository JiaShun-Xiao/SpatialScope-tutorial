SpatialScope
=============================================

A unified approach for integrating spatial and single-cell transcriptomics data by leveraging deep generative models.

With the learned gene expressions distribution from scRNA-seq reference, SpatialScope can resolve the spot-level seq-based ST data (e.g., Visium) into single-cell resolution. Besides, it can also impute unmeasured genes or correct low-quality genes when applied to higher resolution ST data such as Slideseq and MERFISH. 
The inferred single-cell resolution transcriptome-wide expression levels can be applied to various downstream analysis, such as fine-grained cell gradients visualization, detection and visualization of spatially resolved cellular communication and identification of spatially DE genes.

.. image:: mainfig-flowchat.jpg
   :width: 800
   :align: center

.. note::

   This project is under active development.

 
SpatialScope Manuscript
------------------

coming soon...


SpatialScope Installation & Usage
------------------

.. toctree::
   :maxdepth: 2

   installation 
   usage

SpatialScope Tutorials
------------------

.. toctree::
   :maxdepth: 2

   notebooks/Human-Heart 
   notebooks/Mouse-Brain 
   notebooks/Mouse-Cerebellum-Slideseq
   notebooks/Mouse-MOp-MERFISH
   notebooks/Human-Heart-CCell-interaction

