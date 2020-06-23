# FHIR Resource Loader

This channel is a modified version of the example FHIR Listener channel. It allows you to create FHIR resources of any type, not just MeasureReports, without assigning a new ID to each resource (meaning the ID in the payload will be used when creating the resource). Try sending the FHIR resources from [examples.json.zip](../../resources/examples.json.zip) to this channel in order to load resources into the FHIR database.

This channel is dependent on the following code template libraries:

- FHIR Helper Functions
- FHIR DB Operations
