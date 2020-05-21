# FEMA Example Channels

This a collection of channels for converting FEMA CSV reports to MeasureReport resources and vice versa.

All of these channels are dependent on the following code template libraries:

- FHIR Helper Functions
- FHIR SANER Helper Functions

## FEMA - CSV to MeasureReport Channel

This channel consumes a FEMA formatted CSV payload and returns a SANER FEMA MeasureReport resource.

## FEMA - CSV to MeasureReport Bundle Channel

This channel consumes a FEMA formatted CSV payload with one or more data rows and returns a SANER FEMA MeasureReport Bundle resource.

## FEMA - MeasureReport to CSV Channel

This channel consumes a SANER FEMA MeasureReport resource and returns a FEMA formatted CSV response.

## FEMA - MeasureReport Bundle to CSV Channel

This channel consumes a SANER FEMA MeasureReport Bundle resource and returns a FEMA formatted CSV response with one or more data rows.

## Example Data

- [FEMA CSV report](../../resources/fema.csv)
- [FEMA MeasureReport resource](../../resources/fema-measure-report.json)
- [FEMA MeasureReport Bundle resource](../../resources/fema-measure-report-bundle.json)

## Helpful Reference Pages

- [MeasureReport documentation page](https://www.hl7.org/fhir/measurereport.html)
