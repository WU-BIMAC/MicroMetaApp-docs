=======================
What is Micro-Meta App?
=======================
**Micro-Meta App is an easy to use and flexible software for the collection of Microscopy Metadata.**

Micro-Meta App collects Microscopy Hardware, Imaging Acquisition Settings, and Quality Control metadata on the basis of the `4DN-BINA-OME (NBO) Microscopy Metadata Specifications <https://github.com/WU-BIMAC/NBOMicroscopyMetadataSpecs/tree/master/Model/stable%20version/v02-01>`_ which are a suite of scalable an extensions of the `OME data model <https://docs.openmicroscopy.org/ome-model/5.6.1/developers/model-overview.html>`_ and have been developed in the context of the `4D Nucleome (4DN) initiative <https://www.4dnucleome.org/>`_ and the `Bioimaging North America <https://www.bioimagingna.org>`_ `Quality Control and Data Management Working Group <https://www.bioimagingna.org/qc-dm-wg>`_

*****************
Features include:
*****************
* Intuitive graphical user interface metadata collection modality
* Compatibility with the `4DN-BINA-OME (NBO) Microscopy Metadata Specifications <https://github.com/WU-BIMAC/NBOMicroscopyMetadataSpecs/tree/master/Model/stable%20version/v02-01>`_ extension of the `OME data model <https://docs.openmicroscopy.org/ome-model/5.6.1/developers/model-overview.html>`_
* Storage of Microscope Hardware specifications metadata in re-usable  JSON files that can be exchanged with other members of the community
* Easy to use as a standalone app
* Easy to integrate into pre-existing repositories
* Pilot integration into the popular OMERO image data repository

****************
Implementations:
****************
Currently, three implementations of the Micro-Meta App are available on Github.

1. A `standalone version <https://github.com/WU-BIMAC/4DNMicroscopyMetadataToolReactElectron>`_ implemented in Javascript Electron which can be downloaded `here <https://github.com/WU-BIMAC/MicroMetaApp-Electron/releases/latest>`_
2. A `Javascript React <https://github.com/WU-BIMAC/4DNMicroscopyMetadataToolReact>`_ version that can be integrated into any web portal, such as the 4DN Data Portal.
3. An `OMERO plugin <https://github.com/WU-BIMAC/4DNMicroscopyMetadataToolOmero>`_ version that is only available as a pilot implementation on the UMMS-PMM instance of the OMERO server.

.. tip::

  Please Note - If you want to know more about the React and OMERO plugin implementations and if you are interested in using them in your portal or OMERO server please contact: caterina.strambio@umassmed.edu.
