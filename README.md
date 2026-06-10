# Opus API

The Opus API gives authorised partners programmatic access to dental clinic data
including patient journals, invoices, and treatment records. Access is available
to vetted partners under a signed data agreement.

**Base URL:** `https://[tenantID].opusdentalonline.com/api/public/v1`


## Getting access

Access is not self-service. To request API credentials:

1. Contact sam.heyman@opusdental.com to discuss your use case
2. Sign a data processing agreement with Opus
3. Receive your API key and onboarding documentation


## Authentication

All requests require an API key.


## Status and versioning

These APIs are currently in end. Endpoints and response formats will
change over the next 6–12 months. Breaking changes will be communicated in
[changelog.md](docs/changelog.md) with reasonable notice.

Do not build production systems on these endpoints without discussing stability
commitments with Opus first.

## Sandbox

A sandbox environment is available for testing. It returns realistic mock
responses without connecting to live clinic data.

The sandbox uses [Mockoon](https://mockoon.com). Request the config file
and run it locally.

Credentials:
1. Base URL: https://opus-sandbox.eu1.mockoon.app
2. API key: please request access

## Contact

To request API access: 
https://www.opusdental.com/no/opus-support/kontakt-oss

Questions or issues: sam.heyman@opusdental.com


