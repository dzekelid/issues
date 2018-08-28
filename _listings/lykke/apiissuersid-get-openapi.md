---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Get API Issuers
  version: 1.0.0
  description: Get api issuers.
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/Issuers:
    get:
      summary: Get API Issuers
      description: Get api issuers.
      operationId: ApiIssuersGet
      x-api-path-slug: apiissuers-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Issuers
  /api/Issuers/{id}:
    get:
      summary: Get API Issuers
      description: Get api issuers.
      operationId: ApiIssuersByIdGet
      x-api-path-slug: apiissuersid-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Issuers
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---