# CDC Round Trip Example Channels

This collection of channels demonstrates a round trip example starting with CDC formatted CSV data, converting it to a MeasureReport resource, storing that resource in a FHIR facade server, retrieving the MeasureReport based on its ID, and then finally converting it back to the original CSV format.

## Push CDC CSV MeasureReport to Local DB Channel

This channel converts a CDC formatted CSV payload into a MeasureReport resource, and then sends that resource to a FHIR facade server to be stored.

## Pull from local DB return CSV Channel

This channel retrieves a MeasureReport resource by querying the FHIR facade server, and then converts the resource into a CDC formatted CSV.

## Example Data

- [CDC CSV report](../../resources/cdc.csv)

## Helpful Reference Pages

- [MeasureReport documentation page](https://www.hl7.org/fhir/measurereport.html)
