====================
Using Micro-Meta App
====================

Micro-Meta App collects Microscopy Hardware, Imaging Acquisition Settings, and Quality Control metadata on the basis of the `4DN Nucleome-BINA Microscopy Metadata Guidelines <https://arxiv.org/abs/1910.11370>`_ which are an extension of the `OME Core Model <https://docs.openmicroscopy.org/ome-model/5.6.1/developers/model-overview.html>`_ and have been developed in the context of the `4D Nucleome (4DN) initiative <https://www.4dnucleome.org/>`_ and the `Bioimaging North America <https://www.bioimagingna.org>`_ `Quality Control and Data Management Working Group <https://www.bioimagingna.org/qc-dm-wg>`_

One key feature of the `4DN-BINA-OME (NBO) extension of the OME Core Model <https://github.com/WU-BIMAC/NBOMicroscopyMetadataSpecs/tree/master/Model/stable%20version/v02-01>`_ is that in order to make things easier for the user, the metadata guidelines scale with experimental intent and complexity.
Thus the 4DN-BINA extension of the OME Core Model sets up a set of `3 Tiers <https://github.com/WU-BIMAC/NBOMicroscopyMetadataSpecs/tree/master/Tier%20System/stable%20version/v02-01>`_ that sanctions which metadata information has to be provided to facilitate reproducibility and sharing of imaging data in a way that takes into account the scientific questions and techniques being used.

For example, **Tier 1** is set up to represent the **Minimum Information about Fluorescence Microscopy Experiments** guidelines and it recommended when no image analysis or simple image analysis procedures are required for the interpretation of image data.  **Tier 2** is utilized to document **image data that requires advanced image analysis** for knowledge extraction and interpretation. Finally, **Tier 3** is recommended for the **full description of  Microscope Hardware** and should be used by both academic and commercial microscope manufacturers.

In order to facilitate the documentation of Microscopy experiments, **Micro-Meta App incorporates the Tiered Guidelines concept**. As a result, when creating a brand new or when opening an existing Microscope metadata file it is first necessary to select the desired Tier level. This garners maximal flexibility as an existing Microscope metadata file can be successively opened at a higher Tier level while preserving information that had already been entered.

In addition, a Microscope metadata file that is opened at a given Tier level can be later validated and saved at a lower Tier level thus facilitating the gradual accumulation of the required information across multiple sessions.


********************************************
Two Micro-Meta App data processing workflows
********************************************
Micro-Meta App is organized around two data-processing workflows.

A . Manage Instrument
=====================
Manage Instruments allows to create a Tier-specific description of the hardware components of a fluorescence microscope.

A . Manage Settings
===================
Manage Settings allows to create a description of the image acquisition parameters used to acquire a specific imaging dataset.
