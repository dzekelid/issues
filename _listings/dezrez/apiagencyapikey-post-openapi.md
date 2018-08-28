---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Issues an API key for use with the simple role/search endpoints
  version: 1.0.0
  description: Issues an api key for use with the simple role/search endpoints.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/agency/apikey:
    post:
      summary: Issues an API key for use with the simple role/search endpoints
      description: Issues an api key for use with the simple role/search endpoints.
      operationId: Agency_IssueApiKeyBysubjectId
      x-api-path-slug: apiagencyapikey-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: subjectId
        description: The Id of the group to assign a key to
      responses:
        200:
          description: OK
      tags:
      - Issues
      - Keyuse
      - Simple
      - Role
      - Search
      - Endpoints
  /api/coreplatformstate/platformissue:
    post:
      summary: Allows business workflows to post system issues to the platform state
        service.
      description: Allows business workflows to post system issues to the platform
        state service..
      operationId: CorePlatformState_PostPlatformIssueByalertDataContract
      x-api-path-slug: apicoreplatformstateplatformissue-post
      parameters:
      - in: body
        name: alertDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - Business
      - Workflows
      - To
      - Post
      - System
      - Issues
      - To
      - Platform
      - State
      - Service
  /api/coreplatformstate/sendpendingalerts:
    post:
      summary: Sends alerts for all current platform issues.
      description: Sends alerts for all current platform issues..
      operationId: CorePlatformState_SendPendingAlerts
      x-api-path-slug: apicoreplatformstatesendpendingalerts-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sends
      - Alerts
      - Current
      - Platform
      - Issues
  /api/Job:
    post:
      summary: Issues a request that a job be cancelled if possbile
      description: Issues a request that a job be cancelled if possbile.
      operationId: Job_CancelJobBycancellationRequest
      x-api-path-slug: apijob-post
      parameters:
      - in: body
        name: cancellationRequest
        description: The cancellation request
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Issues
      - Request
      - That
      - Job
      - Be
      - Cancelled
      - If
      - Possbile
  /api/credentials/emailsync/usernamepassword:
    post:
      summary: "Creates or Updates Email Sync Security Credentials\r\nThis also uses
        the credentials to do a quick check and see if they are working\r\nit will
        throw an internal server error if there is an issue with the connection\r\nbut
        this may be the server address (s"
      description: "Creates or updates email sync security credentials\r\nthis also
        uses the credentials to do a quick check and see if they are working\r\nit
        will throw an internal server error if there is an issue with the connection\r\nbut
        this may be the server address (s."
      operationId: Credentials_UpsertEmailSyncUsernamePasswordBycredentialDataContract
      x-api-path-slug: apicredentialsemailsyncusernamepassword-post
      parameters:
      - in: body
        name: credentialDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Creates
      - S
      - Email
      - Sync
      - Security
      - "Credentials\r\nThis"
      - Also
      - Uses
      - Credentials
      - To
      - Do
      - Quick
      - Check
      - See
      - If
      - They
      - Are
      - "Working\r\nIt"
      - Will
      - Throw
      - Internal
      - Server
      - Error
      - If
      - There
      - Is
      - Issue
      - "Connection\r\nBut"
      - This
      - May
      - Be
      - Server
      - Address
      - (s
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