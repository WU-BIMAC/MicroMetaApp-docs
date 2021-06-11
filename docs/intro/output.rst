
======
Output
======
Micro-Meta App produces json two kind of structured json file as output, one for the Instrument and one for the Image Acquisition Setting.

***************
Instrument file
***************
The following is an empty example of an Instrument file.
Please note the components array could be filled with any number of json object based on the number of elements that have been added in the instrument.

{
  "Name": "MicroscopeName",
  "Tier": tier,
  "ValidationTier": validationTier,
  "Schema_ID": "Instrument.json",
  "ID": "uuid",
  "Description": " ... ",
  "MicroscopeStand": { ... },
  "AppVersion": "versionNumber",
  "ModelVersion": "versionNumber",
  "components": [ ... ],
  "linkedFields": { .... }
}

*************************
Image Acquisition Setting
*************************
The following is an empty example of an Image Acquisition Setting file.
Please note that the field "StageInsert", "FocusStabilizationDevice", "AcquisitionSoftware", "MicroscopeStandSettings", "Channels", "ObjectiveSettings", "ImagingEnvironment",  "MicroscopeTableSettings", "SamplePositioningSettings" and "Planes" may be absent in your output based on the element that you have created in the application.

{
  "Name": "ImageAcquisitionSetting",
  "AcquisitionDate": "day @ time",
  "Schema_ID": "Image.json",
  "ID": "uuid",
  "Tier": tier,
  "ValidationTier": validationTier,
  "Description": "...",
  "InstrumentName": "MicroscopeName",
  "InstrumentID": "microscope uuid",
  "StageInsert": [ ... ],
  "FocusStabilizationDevice": [ ... ],
  "AcquisitionSoftware": [ ... ],
  "MicroscopeStandSettings" : [ ... ],
  "Channels" : [ ... ],
  "ObjectiveSettings" : { ... },
  "ImagingEnvironment" : [ ... ],
  "MicroscopeTableSettings" : [ ... ],
  "SamplePositioningSettings" : [ ... ],
  "Planes": [ ... ],
  "AppVersion": "versionNumber",
  "ModelVersion": "versionNumber",
  }
