
> [!WARNING]
> This Opus API v1 is currently in active use, however a new v2 is in
> development and will replace v1 in the coming months. New integrations
> should be scoped accordingly — please contact us before starting to discuss
> the v2 timeline.

# Opus API (v1)

The Opus API gives authorised partners programmatic access to dental clinic data
including patient journals, invoices, and treatment records. Access is available
to vetted partners under a signed data agreement.

**Base URL:** `https://[tenantID].opusdentalonline.com/api/public/v1`

## API Reference

The full interactive API reference is available at:
[opus-dental.github.io/api-docs](https://opus-dental.github.io/api-docs/)

The OpenAPI specification can be downloaded directly:
[openapi.json](openapi.json)

## Getting access

Access is not self-service. To request API credentials:

1. Contact us to discuss your use case: [contact form](https://www.opusdental.com/no/opus-support/kontakt-oss)
2. Sign a data processing agreement with Opus
3. Receive your API key and onboarding documentation


## Authentication

All requests require an API key.


## Status and versioning

This API is currently in active use but subject to change. Endpoints and response formats will change over the next 6–12 months. Any breaking changes will be communicated ahead of time in the [changelog](docs/changelog.md) with reasonable notice.

Do not build production systems on these endpoints without discussing stability
commitments with Opus first.

## Sandbox

A sandbox environment is available for testing. It returns realistic mock
responses without connecting to live clinic data.

The sandbox uses [Mockoon](https://mockoon.com). Partners will be given the config file
during the onboarding process.

## Contact

To request API access: 
https://www.opusdental.com/no/opus-support/kontakt-oss

Questions or issues please contact: sam.heyman@opusdental.com


