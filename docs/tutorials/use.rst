====================
Using Micro-Meta App
====================

Micro-Meta App collects Microscopy Hardware, Imaging Acquisition Settings, and Quality Control metadata on the basis of the `4DN Nucleome-BINA Microscopy Metadata Guidelines <https://arxiv.org/abs/1910.11370>`_ which are an extension of the `OME Core Model <https://docs.openmicroscopy.org/ome-model/5.6.1/developers/model-overview.html>`_ and have been developed in the context of the `4D Nucleome (4DN) initiative <https://www.4dnucleome.org/>`_ and the `Bioimaging North America <https://www.bioimagingna.org>`_ `Quality Control and Data Management Working Group <https://www.bioimagingna.org/qc-dm-wg>`_

One key feature of the `4DN-BINA extension of the OME Core Model <https://github.com/WU-BIMAC/MicroscopyMetadata4DNGuidelines/tree/master/Model/stable%20version/v01-07>`_ is that in order to make things easier for the user, the metadata guidelines scale with experimental intent and complexity.
Thus the 4DN-BINA extension of the OME Core Model sets up a set of `5 Tiers <https://github.com/WU-BIMAC/MicroscopyMetadata4DNGuidelines/tree/master/Tier%20System/stable%20version/v01-01>`_ that sanctions which metadata information has to be provided to facilitate reproducibility and sharing of imaging data in a way that takes into account the scientific questions and techniques being used.

For example, **Tier 1** is set up to represent the **Minimum Information about Fluorescence Microscopy Experiment** guidelines and it recommended when no image analysis is required for the interpretation of image data.  **Tier 3** is utilized to document **image data that requires advanced image analysis** for knowledge extraction and interpretation. Finally, **Tier 5** is recommended for the **full description of  Microscope Hardware** and should be used by both academic and commercial microscope manufacturers.

In order to facilitate the documentation of Microscopy experiments, **Micro-Meta App incorporates the Tiered Guidelines concept**. As a result, when creating a brand new or when opening an existing Microscope metadata file it is first necessary to select the desired Tier level. This garners maximal flexibility as an existing Microscope metadata file can be successively opened at a higher Tier level while preserving information that had already been entered.

In addition, a Microscope metadata file that is opened at a given Tier level can be later validated and saved at a lower Tier level thus facilitating the gradual accumulation of the required information across multiple sessions.

******************************************
A. Managing Microscope Specification files
******************************************
Please follow these step by step instructions.

A.1 Selecting Tier level
========================
Click on the "Tier" selector and select the Tier level you are interested in and click on “Create microscope”.

.. tip::

  Please note that a Microscope metadata file that has been opened at a given Tier level can be validated and saved at a lower level, thus facilitating the work required for full documentation by allowing it to be done over multiple sessions.

.. .. figure:: images/use_images/01_Select-Tier_1.png
..   :class: shadow-image
..   :width: 90%
..   :align: center

.. Figure 1: Click on the Tier selection menu.

.. ------

.. figure:: images/use_images/02_Select-Tier_2.png
  :class: shadow-image
  :width: 90%
  :align: center

  Figure 1: Select the desired Tier level.

A.2 Creating or Opening a Microscope file
=========================================
After selecting the desired Tier level, select one of the three options by clicking on the on the "Create Microscope" selector. “Create from scratch” allows to create a new Microscope file. “Load from file” allows to import a Microscope file that has not been loaded in the App yet (i.e., a Microscope file you might have received from someone else). “Load from repository” allows to work on a Microscope file that has already been imported in the App and you might need to modify.

A.2.1 Creating from scratch
---------------------------
After selecting “Create from scratch”, hit “Confirm” and an empty Canvas will appear. To start building a new Microscope file, first hit “Edit Microscope”, enter the required attributes and hit “Confirm”. To add Hardware components follow instructions below.

A.2.2 Loading from file
-----------------------
Step 1
^^^^^^
After selecting “Load from file”, hit “Confirm” and click to select an existing Microscope file obtained from a third party.

.. .. figure:: images/use_images/04_Load_from_file_1.png
..   :class: shadow-image
..   :width: 90%
..   :align: center

..  Figure 2: Select “Load from file” to open an existing third-party Microscope file.

Step 2
^^^^^^
Select the desired Microscope file (i.e., those provided as Example Files with the App), click “Open” and then hit “Confirm”.

.. figure:: images/use_images/05_Load_from_file_2.png
  :class: shadow-image
  :width: 90%
  :align: center

  Figure 2: Select the desired Microscope file to open.


A.2.3 Loading from the Repository/Home folder
---------------------------------------------
Step 1
^^^^^^
Select “Load from repository” to open an existing Microscope file to edit, and hit “Confirm”.

.. figure:: images/use_images/06_Load_from_repository_1.png
  :class: shadow-image
  :width: 90%
  :align: center

  Figure 3: Select “Load from repository” to open an existing Microscope file to edit.

Step 2
^^^^^^
First select the Manufacturer of the Microscope and then select the desired Microscope file you need to edit.

.. figure:: images/use_images/07_Load_from_repository_2.png
  :class: shadow-image
  :width: 90%
  :align: center

  Figure 4: Select the desired manufacturer and Microscope file from those available in the Repository/Home folder.

A.3 Adding and Editing Hardware components to the Canvas
========================================================
After opening a new or an existing Microscope file, if available all pre-existing Hardware components will appear on the Canvas. In this example the TIRF Epi-Fluorescence Structured Light Microscope `(TESM) <https://trello.com/b/BQ8zCcQC/tirf-epi-fluorescence-structured-light-microscope>`_ custom built at the University of Massachusetts Medical School `Program in Molecular Medicine <https://www.umassmed.edu/pmm>`_ by members of the `Bio-Medical Imaging Group <http://big.umassmed.edu>`_, is displayed with several existing components.

.. figure:: images/use_images/08_Open_Microscope.png
  :class: shadow-image
  :width: 90%
  :align: center

  Figure 5: The opened TESM Microscope file with existing Hardware components.

.. tip::

  At any time in the process it is possible to click on the "Back" button to navigate back to the the opening screen to work on a different Microscope metadata
  file or to choose a different Tier level for the current Microscope.

Step 1
------
In order to add additional Hardware components, select and open one of the sections [1] on the right panel, and select a new element to add [2]. In this example, we are selecting and adding a new Objective to the Canvas.

.. figure:: images/use_images/09_Add_new_Objective.png
  :class: shadow-image
  :width: 90%
  :align: center

  Figure 6: Add a new Objective component to the Microscope canvas.

Step 2
------
A newly added element will appear with a red box around it indicating that metadata values are missing and that the component is not validated. In order to enter metadata values, click on the element to open the associated form.
Fields that are mandatory for the Tier-validation level you have selected are marked by an asterisk. After entering metadata values, when you click “Confirm” the App will take you to fields (marked by red error messages) that are still missing and need to be filled in to complete validation.

.. figure:: images/use_images/10_Edit_attributes.png
  :class: shadow-image
  :width: 90%
  :align: center

  Figure 7: Edit Objective’s attributes.

-----

.. figure:: images/use_images/11_Confirm_attributes.png
  :class: shadow-image
  :width: 90%
  :align: center

  Figure 8: Enter the required Objective’s attributes and Confirm to validate.


Step 3
------
In the case of Filters, Dichroic, and LED light sources, it is possible to add multiple Transmittance, Reflectance, and Wavelength Ranges to reflect the multi-pass nature of the component. In order to add additional band-pass components click on “Edit Component”.  In order to edit the number of band-pass components click on + or -.  IMPORTANT: if you change the number of band-pass components after you have started adding values in the metadata fields, all un-saved values previously entered will be lost (this is obviously not great and we are planning to fix this issue in a future release. For now please accept our apologies for the temporary inconvenience).

.. figure:: images/use_images/12_Add_Transmittance-Range.png
  :class: shadow-image
  :width: 90%
  :align: center

  Figure 9: Add the required number of Transmittance Range components to correctly describe a multi-pass Excitation filter.

A.4 Saving Microscope files
===========================
In order to facilitate entering the require microscopy hardware metadata over multiple sessions, before saving the Tier level used to validate the Microscope metadata file can be changed by clicking on the "Validate @Tier: " selector. After that, the Microscope metadata file can be can be saved to the Repository/Home folder or exported as a file by clicking on the "Save microscope" selector. Finally, after saving a Microscope metadata file, it is possible to navigate back to the Micro-Meta App opening screen to work on a different Microscope metadata file or to choose a different Tier level for the current Microscope.

.. figure:: images/use_images/14_Change_Validation-Tier.png
  :class: shadow-image
  :width: 90%
  :align: center

  Figure 10: Changing validation Tier, saving the Microscope metadata file, and navigating back to the opening screen.
