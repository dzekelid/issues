swagger: "2.0"
x-collection-name: Lykke
x-complete: 1
info:
  title: Wallet_Api
  version: 1.0.0
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