---
name: google-data-get-and-update-sheet-by-data-filter
description: Retrieve values from a Google Sheet using a data filter and then update values using a data filter.
api: openapi/google-data-api-openapi.yml
operations:
- postV4SpreadsheetsBySpreadsheetIdValues:batchGetByDataFilter
- postV4SpreadsheetsBySpreadsheetIdValues:batchUpdateByDataFilter
- postV4Spreadsheets{spreadsheetId}:getByDataFilter
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/google-data-api-openapi.yml ; every operationId checked against the contract
---

# google-data-get-and-update-sheet-by-data-filter

Retrieve values from a Google Sheet using a data filter and then update values using a data filter.

## Steps

1. 1. Call `postV4SpreadsheetsBySpreadsheetIdValues:batchGetByDataFilter` with the required path parameter `spreadsheetId` and request body specifying the data filter.
2. 2. Call `postV4SpreadsheetsBySpreadsheetIdValues:batchUpdateByDataFilter` with the same `spreadsheetId` and a request body containing the data filter and the values to write.
3. 3. Call `postV4Spreadsheets{spreadsheetId}:getByDataFilter` with `spreadsheetId` and a request body defining the data filter to retrieve the updated sheet.

## Rules

- Include an authentication header: either `x-goog-api-key` with an API key or an OAuth2 bearer token as defined by the provider.
- No rate‑limit information is provided; assume no specific limit.
- Operations are not documented as paginated; handle responses as single pages.
