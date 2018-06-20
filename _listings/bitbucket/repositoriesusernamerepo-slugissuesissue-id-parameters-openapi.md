---
swagger: "2.0"
x-collection-name: Bitbucket
x-complete: 0
info:
  title: Bitbucket Parameters Repositories Username Repo Slug Issues Issue
  description: Parameters repositories username repo slug issues issue
  termsOfService: https://www.atlassian.com/legal/customer-agreement
  contact:
    name: Bitbucket Support
    url: https://support.atlassian.com/bitbucket
    email: support@bitbucket.org
  version: 1.0.0
host: api.bitbucket.org
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /repositories/{username}/{repo_slug}/issues:
    get:
      summary: Get Repositories Username Repo Slug Issues
      description: Get repositories username repo slug issues
      operationId: getRepositoriesUsernameRepoSlugIssues
      x-api-path-slug: repositoriesusernamerepo-slugissues-get
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Issues
    parameters:
      summary: Parameters Repositories Username Repo Slug Issues
      description: Parameters repositories username repo slug issues
      operationId: parametersRepositoriesUsernameRepoSlugIssues
      x-api-path-slug: repositoriesusernamerepo-slugissues-parameters
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Issues
    post:
      summary: Add Repositories Username Repo Slug Issues
      description: |-
        Creates a new issue.

        This call requires authentication. Private repositories or private
        issue trackers require the caller to authenticate with an account that
        has appropriate authorisation.

        The authenticated user is used for the issue's `reporter` field.
      operationId: postRepositoriesUsernameRepoSlugIssues
      x-api-path-slug: repositoriesusernamerepo-slugissues-post
      parameters:
      - in: body
        name: _body
        description: The new issue
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Issues
  /repositories/{username}/{repo_slug}/issues/{issue_id}:
    delete:
      summary: Delete Repositories Username Repo Slug Issues Issue
      description: |-
        Deletes the specified issue. This requires write access to the
        repository.
      operationId: deleteRepositoriesUsernameRepoSlugIssuesIssue
      x-api-path-slug: repositoriesusernamerepo-slugissuesissue-id-delete
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Issues
      - Issue
    get:
      summary: Get Repositories Username Repo Slug Issues Issue
      description: Get repositories username repo slug issues issue
      operationId: getRepositoriesUsernameRepoSlugIssuesIssue
      x-api-path-slug: repositoriesusernamerepo-slugissuesissue-id-get
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Issues
      - Issue
    parameters:
      summary: Parameters Repositories Username Repo Slug Issues Issue
      description: Parameters repositories username repo slug issues issue
      operationId: parametersRepositoriesUsernameRepoSlugIssuesIssue
      x-api-path-slug: repositoriesusernamerepo-slugissuesissue-id-parameters
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Issues
      - Issue
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