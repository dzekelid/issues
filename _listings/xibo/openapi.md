swagger: "2.0"
x-collection-name: Xibo
x-complete: 1
info:
  title: Xibo API
  description: xibo-cms-api
  termsOfService: http://xibo.org.uk/legal
  version: 1.0.0
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /display/wol/{displayId}:
    post:
      summary: Issue WOL
      description: Send a Wake On LAN packet to this Display
      operationId: displayWakeOnLan
      x-api-path-slug: displaywoldisplayid-post
      parameters:
      - in: path
        name: displayId
        description: The Display ID
      responses:
        200:
          description: OK
      tags:
      - Issue
      - WOL