# Cloud Assessment Tool Server

## Outline

The [Cloud Assessment Tool (CAT)](assess.cloud.gov.au) is designed to help Australian Government agencies discover and understand their compliance obligations when moving to cloud. It is part of the [Digital Transformation Agency's](dta.gov.au) [Secure Cloud Strategy](https://www.dta.gov.au/what-we-do/policies-and-programs/secure-cloud/).

The CAT Server is used for uploading and storing completed reports from the CAT front-end.

## Production deployment

The CAT Server is designed to be hosted on cloud.gov.au using CircleCI for deployments. The Cloud Foundry manifest is available at `manifest.yml`. The CircleCI config is available at `.circleci/config.yml`.

## Client-side application

The client-side app is available in the [cloud-assessment](https://github.com/govau/cloud-assessment) repository on GitHub.

## Development server

Run `node server.js`.