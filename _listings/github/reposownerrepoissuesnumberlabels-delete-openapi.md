---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Delete Repos Owner Repo Issues Number Labels
  description: Remove all labels from an issue.
  termsOfService: https://help.github.com/articles/github-terms-of-service/#b-api-terms
  version: 1.0.0
host: api.github.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /issues:
    get:
      summary: Get Issues
      description: |-
        List issues.
        List all issues across all the authenticated user's visible repositories.
      operationId: list-issueslist-all-issues-across-all-the-authenticated-users-visible-repositories
      x-api-path-slug: issues-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: direction
      - in: query
        name: filter
        description: Issues assigned to you / created by you / mentioning you / youresubscribed
          to updates for / All issues the authenticated user can see
      - in: query
        name: labels
        description: String list of comma separated Label names
      - in: query
        name: since
        description: 'Optional string of a timestamp in ISO 8601 format: YYYY-MM-DDTHH:MM:SSZ'
      - in: query
        name: sort
      - in: query
        name: state
      responses:
        200:
          description: OK
      tags:
      - Issues
  /legacy/issues/search/{owner}/{repository}/{state}/{keyword}:
    get:
      summary: Get Legacy Issues Search Owner Repository State Keyword
      description: Find issues by state and keyword.
      operationId: find-issues-by-state-and-keyword
      x-api-path-slug: legacyissuessearchownerrepositorystatekeyword-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: keyword
        description: The search term
      - in: path
        name: owner
      - in: path
        name: repository
      - in: path
        name: state
        description: Indicates the state of the issues to return
      responses:
        200:
          description: OK
      tags:
      - Legacy
      - Issues
      - Search
      - Owner
      - Repository
      - State
      - Keyword
  /orgs/{org}/issues:
    get:
      summary: Get Orgs Org Issues
      description: |-
        List issues.
        List all issues for a given organization for the authenticated user.
      operationId: list-issueslist-all-issues-for-a-given-organization-for-the-authenticated-user
      x-api-path-slug: orgsorgissues-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: direction
      - in: query
        name: filter
        description: Issues assigned to you / created by you / mentioning you / youresubscribed
          to updates for / All issues the authenticated user can see
      - in: query
        name: labels
        description: String list of comma separated Label names
      - in: path
        name: org
        description: Name of organisation
      - in: query
        name: since
        description: 'Optional string of a timestamp in ISO 8601 format: YYYY-MM-DDTHH:MM:SSZ'
      - in: query
        name: sort
      - in: query
        name: state
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Issues
  /repos/{owner}/{repo}/issues:
    get:
      summary: Get Repos Owner Repo Issues
      description: List issues for a repository.
      operationId: list-issues-for-a-repository
      x-api-path-slug: reposownerrepoissues-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: direction
      - in: query
        name: filter
        description: Issues assigned to you / created by you / mentioning you / youresubscribed
          to updates for / All issues the authenticated user can see
      - in: query
        name: labels
        description: String list of comma separated Label names
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      - in: query
        name: since
        description: 'Optional string of a timestamp in ISO 8601 format: YYYY-MM-DDTHH:MM:SSZ'
      - in: query
        name: sort
      - in: query
        name: state
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
    post:
      summary: Add Repos Owner Repo Issues
      description: |-
        Create an issue.
        Any user with pull access to a repository can create an issue.
      operationId: create-an-issueany-user-with-pull-access-to-a-repository-can-create-an-issue
      x-api-path-slug: reposownerrepoissues-post
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
  /repos/{owner}/{repo}/issues/comments:
    get:
      summary: Get Repos Owner Repo Issues Comments
      description: List comments in a repository.
      operationId: list-comments-in-a-repository
      x-api-path-slug: reposownerrepoissuescomments-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: direction
        description: Ignored without sort parameter
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      - in: query
        name: since
        description: 'The time should be passed in as UTC in the ISO 8601 format:
          YYYY-MM-DDTHH:MM:SSZ'
      - in: query
        name: sort
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
      - Comments
  /repos/{owner}/{repo}/issues/comments/{commentId}:
    delete:
      summary: Delete Repos Owner Repo Issues Comments Comment
      description: Delete a comment.
      operationId: delete-a-comment
      x-api-path-slug: reposownerrepoissuescommentscommentid-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: commentId
        description: ID of comment
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
      - Comments
      - Comment
    get:
      summary: Get Repos Owner Repo Issues Comments Comment
      description: Get a single comment.
      operationId: get-a-single-comment
      x-api-path-slug: reposownerrepoissuescommentscommentid-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: commentId
        description: ID of comment
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
      - Comments
      - Comment
    patch:
      summary: Patch Repos Owner Repo Issues Comments Comment
      description: Edit a comment.
      operationId: edit-a-comment
      x-api-path-slug: reposownerrepoissuescommentscommentid-patch
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: commentId
        description: ID of comment
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
      - Comments
      - Comment
  /repos/{owner}/{repo}/issues/events:
    get:
      summary: Get Repos Owner Repo Issues Events
      description: List issue events for a repository.
      operationId: list-issue-events-for-a-repository
      x-api-path-slug: reposownerrepoissuesevents-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
      - Events
  /repos/{owner}/{repo}/issues/events/{eventId}:
    get:
      summary: Get Repos Owner Repo Issues Events Event
      description: Get a single event.
      operationId: get-a-single-event
      x-api-path-slug: reposownerrepoissueseventseventid-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: eventId
        description: Id of the event
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
      - Events
      - Event
  /repos/{owner}/{repo}/issues/{number}:
    get:
      summary: Get Repos Owner Repo Issues Number
      description: Get a single issue
      operationId: get-a-single-issue
      x-api-path-slug: reposownerrepoissuesnumber-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: number
        description: Number of issue
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
      - Number
    patch:
      summary: Patch Repos Owner Repo Issues Number
      description: |-
        Edit an issue.
        Issue owners and users with push access can edit an issue.
      operationId: edit-an-issueissue-owners-and-users-with-push-access-can-edit-an-issue
      x-api-path-slug: reposownerrepoissuesnumber-patch
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: number
        description: Number of issue
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
      - Number
  /repos/{owner}/{repo}/issues/{number}/comments:
    get:
      summary: Get Repos Owner Repo Issues Number Comments
      description: List comments on an issue.
      operationId: list-comments-on-an-issue
      x-api-path-slug: reposownerrepoissuesnumbercomments-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: number
        description: Number of issue
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
      - Number
      - Comments
    post:
      summary: Add Repos Owner Repo Issues Number Comments
      description: Create a comment.
      operationId: create-a-comment
      x-api-path-slug: reposownerrepoissuesnumbercomments-post
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: number
        description: Number of issue
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
      - Number
      - Comments
  /repos/{owner}/{repo}/issues/{number}/events:
    get:
      summary: Get Repos Owner Repo Issues Number Events
      description: List events for an issue.
      operationId: list-events-for-an-issue
      x-api-path-slug: reposownerrepoissuesnumberevents-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: number
        description: Number of issue
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
      - Number
      - Events
  /repos/{owner}/{repo}/issues/{number}/labels:
    delete:
      summary: Delete Repos Owner Repo Issues Number Labels
      description: Remove all labels from an issue.
      operationId: remove-all-labels-from-an-issue
      x-api-path-slug: reposownerrepoissuesnumberlabels-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: number
        description: Number of issue
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
      - Number
      - Labels
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