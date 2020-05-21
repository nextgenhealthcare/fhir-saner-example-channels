# FHIR SANER Example Channels and Code Template Libraries

## Situational Awareness for Novel Epidemic Response (SANER)

This repository contains channels and code template libraries that were developed to test the SANER implementation guide.

## How To Get Started

### Setting up FHIR facade server

Refer to this [guide](http://www.mirthcorp.com/community/wiki/display/mirth/Example+Channel+(R4)). In the **Importing the Example Channel** section, instead of importing **Example - FHIR Listener (3.9.0).xml**, import the [FHIR Listener.xml](channels/FHIR%20Listener/FHIR%20Listener.xml) channel included in this repository.

### Importing SANER channels and code template libraries

If you are looking to consume or produce CDC CSVs or MeasureReports, you can find example channels in the [CDC - CSV MeasureReport Conversions](channels/CDC%20-%20CSV%20MeasureReport%20Conversions) folder.

If you are looking to consume or produce FEMA CSVs or MeasureReports, you can find example channels in the [FEMA - CSV MeasureReport Conversions](channels/FEMA%20-%20CSV%20MeasureReport%20Conversions) folder.

If you would like to see a round trip example in which CDC CSV data is converted to a MeasureReport, stored in the FHIR facade server, retrieved from the server, and converted back to CSV, you can find example channels in the [CDC - CSV MeasureReport Round Trip](channels/CDC%20-%20CSV%20MeasureReport%20Round%20Trip) folder.

### Example Data

The [resources](resources) folder contains example CDC and FEMA CSV files, MeasureReports, and MeasureReport Bundles. In that folder you can also find  [examples.json.zip](resources/examples.json.zip) which contains a collection of FHIR resources that you can send to the example FHIR Listener channel.

## Helpful Reference Pages

[The SANER Project](http://build.fhir.org/ig/HL7/fhir-saner/overview.html)
