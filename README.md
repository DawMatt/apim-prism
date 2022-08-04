# Azure API Management Prism

Azure API Management with Stoplight Prism mocked APIs.

## Goals

### Core Functionality

- Instantiate the Prism Docker container
- Add configured APIs to Prism container and initiate mocking for all
- Add configured APIs to APIM instance and setup to point to the matching Prism mocks
- GitHub Actions for automatically redeploying when APIs are added or modified

### Extended Functionality

- Install Azure API Management Consumption instance
- Build and publish Docker container including Stoplight Prism
- Manually initiated or restricted scope (e.g. specific folder) GitHub Actions for extended functionality

## Configuration

- GitHub secrets
- configuration files for API URI Paths for APIM and the mocks
