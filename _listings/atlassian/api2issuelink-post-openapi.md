---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Jira Cloud API Link issues
  description: Creates an issue link between two issues. The user requires the link
    issue permission for the issue which will be linked to another issue. The specified
    link type in the request is used to create the link and will create a link from
    the first issue to the second issue using the outward description. It also create
    a link from the second issue to the first issue using the inward description of
    the issue link type. It will add the supplied comment to the first issue. The
    comment can have a restriction who can view it. If group is specified, only users
    of this group can view this comment, if roleLevel is specified only users who
    have the specified role can view this comment. The user who creates the issue
    link needs to belong to the specified group or have the specified role.
  termsOfService: http://atlassian.com/terms/
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/2/component/{id}/relatedIssueCounts:
    get:
      summary: Get component issues count
      description: Returns the counts of issues assigned to the component. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
        required:** Permission to access Jira.
      operationId: com.atlassian.jira.rest.v2.issue.ComponentResource.getComponentRelatedIssues_get
      x-api-path-slug: api2componentidrelatedissuecounts-get
      parameters:
      - in: path
        name: id
        description: The ID of the component
      responses:
        200:
          description: OK
      tags:
      - Component
      - Issues
      - Count
  /api/2/issue/bulk:
    post:
      summary: Create issues
      description: |-
        Creates multiple issues or sub-tasks from a JSON representation, in a single bulk operation.

        Creating a sub-task is similar to creating an issue - check Create issue section for details: {@link IssueResource#createIssue(boolean, IssueUpdateBean)}}
      operationId: com.atlassian.jira.rest.v2.issue.IssueResource.createIssues_post
      x-api-path-slug: api2issuebulk-post
      responses:
        200:
          description: OK
      tags:
      - Issues
  /api/2/issueLink:
    post:
      summary: Link issues
      description: Creates an issue link between two issues. The user requires the
        link issue permission for the issue which will be linked to another issue.
        The specified link type in the request is used to create the link and will
        create a link from the first issue to the second issue using the outward description.
        It also create a link from the second issue to the first issue using the inward
        description of the issue link type. It will add the supplied comment to the
        first issue. The comment can have a restriction who can view it. If group
        is specified, only users of this group can view this comment, if roleLevel
        is specified only users who have the specified role can view this comment.
        The user who creates the issue link needs to belong to the specified group
        or have the specified role.
      operationId: com.atlassian.jira.rest.v2.issue.LinkIssueResource.linkIssues_post
      x-api-path-slug: api2issuelink-post
      responses:
        200:
          description: OK
      tags:
      - Link
      - Issues
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