# CDC Example Channels

This a collection of channels for converting CDC CSV reports to MeasureReport resources and vice versa.

All of these channels are dependent on the following code template libraries:

- FHIR Helper Functions
- FHIR SANER Helper Functions

## CDC - CSV to MeasureReport Channel

This channel consumes a CDC formatted CSV payload and returns a SANER CDC MeasureReport resource.

## CDC - CSV to MeasureReport Bundle Channel

This channel consumes a CDC formatted CSV payload with one or more data rows and returns a SANER CDC MeasureReport Bundle resource.

## CDC - MeasureReport to CSV Channel

This channel consumes a SANER CDC MeasureReport resource and returns a CDC formatted CSV response.

## CDC - MeasureReport Bundle to CSV Channel

This channel consumes a SANER CDC MeasureReport Bundle resource and returns a CDC formatted CSV response with one or more data rows.

## Example Data

- [CDC CSV report](../../resources/cdc.csv)
- [CDC MeasureReport resource](../../resources/cdc-measure-report.json)
- [CDC MeasureReport Bundle resource](../../resources/cdc-measure-report-bundle.json)

## Helpful Reference Pages

- [MeasureReport documentation page](https://www.hl7.org/fhir/measurereport.html)
