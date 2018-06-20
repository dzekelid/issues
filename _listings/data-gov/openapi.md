---
swagger: "2.0"
x-collection-name: Data.Gov
x-complete: 1
info:
  title: Data.gov API
  description: the-data-gov-catalog-is-powered-by-ckan-a-powerful-open-source-data-platform-that-includes-a-robust-api--please-be-aware-that-data-gov-and-the-data-gov-ckan-api-only-contain-metadata-about-datasets--this-metadata-includes-urls-and-descriptions-of-datasets-but-it-does-not-include-the-actual-data-within-each-dataset-
  version: "3"
host: catalog.data.gov
basePath: /api/3/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /issues/:
    get:
      summary: Get Issues
      description: List all Issues
      operationId: getIssues
      x-api-path-slug: issues-get
      parameters:
      - in: query
        name: closed
        description: Filter closed issues
      - in: query
        name: for
        description: Filter issues for a given subject
      - in: query
        name: page
        description: The page to fetch
      - in: query
        name: page_size
        description: The page size to fetch
      - in: query
        name: sort
        description: The sorting attribute
      responses:
        200:
          description: OK
      tags:
      - Issues
    post:
      summary: Add Issues
      description: Create a new Issue
      operationId: postIssues
      x-api-path-slug: issues-post
      parameters:
      - in: body
        name: payload
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Issues
  /issues/{id}/:
    get:
      summary: Get Issues
      description: Get an issue given its ID
      operationId: getIssues
      x-api-path-slug: issuesid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Issues
    post:
      summary: Add Issues
      description: Add comment and optionnaly close an issue given its ID
      operationId: postIssues
      x-api-path-slug: issuesid-post
      parameters:
      - in: path
        name: id
      - in: body
        name: payload
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Issues
  /me/org_issues/:
    get:
      summary: Get Me Org Issues
      description: List all issues related to my organizations
      operationId: getMeOrgIssues
      x-api-path-slug: meorg-issues-get
      parameters:
      - in: query
        name: q
        description: The string to filter items
      responses:
        200:
          description: OK
      tags:
      - Me
      - Org
      - Issues
  /organizations/{org}/issues/:
    get:
      summary: Get Organizations Org Issues
      description: List organization issues
      operationId: getOrganizationsOrgIssues
      x-api-path-slug: organizationsorgissues-get
      parameters:
      - in: path
        name: org
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Org
      - Issues
---