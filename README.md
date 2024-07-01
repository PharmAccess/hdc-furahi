# hdc-furahi

Demonstrator of composable FHIR data stack

## About the project name

Furaha describes feelings of happiness and joy. It is used often during happy and joyful ceremonies to encourage the crowd to enjoy themselves. If you’re using it to encourage someone else, the word becomes furahia or furahi, literally translated as 'be happy'. Furahi is also a play on the letters of FHIR.

## Anonimized data set

The dataset for this demonstrator is an anonimized version of mothers in Tanzania. It is based on a maternal care program in Hanang district, Tanzania. As some files exceed the 25 MB limit on GitHub (`Encounter`, `Procedure`, `QuestionnaireResponse`), the full dataset is hosted on google cloud storage as bulk fhir data (ndjson). The url to each file follows the pattern `https://storage.googleapis.com/hanang-anonymized-maternal-care-data/{resourceType}.ndjson`:

* [patient](https://storage.googleapis.com/hanang-anonymized-maternal-care-data/patient.ndjson)
* [observation](https://storage.googleapis.com/hanang-anonymized-maternal-care-data/observation.ndjson)
* [condition](https://storage.googleapis.com/hanang-anonymized-maternal-care-data/condition.ndjson)
* [encounter](https://storage.googleapis.com/hanang-anonymized-maternal-care-data/encounter.ndjson)
* [procedure](https://storage.googleapis.com/hanang-anonymized-maternal-care-data/procedure.ndjson)
* [episodeOfCare](https://storage.googleapis.com/hanang-anonymized-maternal-care-data/episodeOfCare.ndjson)
* [organization](https://storage.googleapis.com/hanang-anonymized-maternal-care-data/organization.ndjson)
* [location](https://storage.googleapis.com/hanang-anonymized-maternal-care-data/location.ndjson)
* [questionnaire](https://storage.googleapis.com/hanang-anonymized-maternal-care-data/questionnaire.ndjson)
* [questionnaireResponse](https://storage.googleapis.com/hanang-anonymized-maternal-care-data/questionnaireResponse.ndjson)
* [serviceRequest](https://storage.googleapis.com/hanang-anonymized-maternal-care-data/serviceRequest.ndjson)

