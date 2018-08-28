---
name: Atlassian
x-slug: atlassian
description: Millions of users globally rely on Atlassian products every day for improving
  software development, project management, collaboration, and code quality.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
x-kinRank: "8"
x-alexaRank: "1656"
tags: Issues
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/apis.md
specificationVersion: "0.14"
apis:
- name: Jira Cloud REST API - Get component issues count
  x-api-slug: api2componentidrelatedissuecounts-get
  description: Returns the counts of issues assigned to the component. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2componentidrelatedissuecounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2componentidrelatedissuecounts-get-openapi.md
- name: Jira Cloud REST API - Create issues
  x-api-slug: api2issuebulk-post
  description: |-
    Creates multiple issues or sub-tasks from a JSON representation, in a single bulk operation.

    Creating a sub-task is similar to creating an issue - check Create issue section for details: {@link IssueResource#createIssue(boolean, IssueUpdateBean)}}
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuebulk-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuebulk-post-openapi.md
- name: Jira Cloud REST API - Link issues
  x-api-slug: api2issuelink-post
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelink-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelink-post-openapi.md
- name: Jira Cloud REST API - Find users assignable to issues
  x-api-slug: api2userassignablesearch-get
  description: |-
    Returns a list of users that can be assigned to an issue. Use this method to find the list of users who can be assigned to:

    *   a new issue, by providing the `projectKeyOrId`.
    *   an updated issue, by providing the `issueKey`.
    *   to an issue during a transition (workflow action), by providing the `issueKey` and the transition id in `actionDescriptorId`. You can obtain the IDs of an issue's valid transitions using the `transitions` option in the `expand` parameter of [Get issue](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issue-issueIdOrKey-get).

    In all these cases, you can pass a username to determine if a user can be assigned to an issue. The user is returned in the response if they can be assigned to the issue or issue transition. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2userassignablesearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2userassignablesearch-get-openapi.md
- name: Jira Cloud REST API - Get version's related issues count
  x-api-slug: api2versionidrelatedissuecounts-get
  description: |-
    Returns the following counts for a version:

    *   Number of issues where the `fixVersion` is set to the version.
    *   Number of issues where the `affectedVersion` is set to the version.
    *   Number of issues where a version custom field is set to the version.

    [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required: _Browse projects_ project permission
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2versionidrelatedissuecounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2versionidrelatedissuecounts-get-openapi.md
- name: Jira Cloud REST API - Get version's unresolved issues count
  x-api-slug: api2versionidunresolvedissuecount-get
  description: 'Returns counts of the issues and unresolved issues for the project
    version. [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required: _Browse
    projects_ project permission'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2versionidunresolvedissuecount-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2versionidunresolvedissuecount-get-openapi.md
- name: Jira Cloud REST API - Merge versions
  x-api-slug: api2versionidmergetomoveissuesto-put
  description: Merges two project versions. The merge is completed by deleting the
    version specified in `id` and replacing any occurrences of its ID in `fixVersion`
    with the version ID specified in `moveIssuesTo`. Consider using [Delete and replace
    version](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-version-id-removeAndSwap-post)
    instead. This resource supports swapping version values in `fixVersion`, `affectedVersion`,
    and custom fields. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
    or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2versionidmergetomoveissuesto-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2versionidmergetomoveissuesto-put-openapi.md
- name: Jira Cloud REST API - Get all issue field options
  x-api-slug: api2fieldfieldkeyoption-get
  description: |-
    Returns all options defined for a select list issue field. A select list issue field is a type of [issue field](https://developer.atlassian.com/cloud/jira/platform/modules/issue-field/) that allows a user to select an value from a list of options.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoption-get-openapi.md
- name: Jira Cloud REST API - Create issue field option
  x-api-slug: api2fieldfieldkeyoption-post
  description: |-
    Creates an option for a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoption-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoption-post-openapi.md
- name: Jira Cloud REST API - Get selectable issue field options
  x-api-slug: api2fieldfieldkeyoptionsuggestionsedit-get
  description: |-
    Returns options defined for a select list issue field that can be viewed and selected by the currently logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionsedit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionsedit-get-openapi.md
- name: Jira Cloud REST API - Get visible issue field options
  x-api-slug: api2fieldfieldkeyoptionsuggestionssearch-get
  description: |-
    Returns options defined for a select list issue field that can be viewed by the currently logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionssearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionssearch-get-openapi.md
- name: Jira Cloud REST API - Get issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-get
  description: |-
    Returns an option from a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-get-openapi.md
- name: Jira Cloud REST API - Update issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-put
  description: |-
    Updates an option for a select list issue field. If the option does not exist, a new option is created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-put-openapi.md
- name: Jira Cloud REST API - Delete issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-delete
  description: |-
    Deletes an option from a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-delete-openapi.md
- name: Jira Cloud REST API - Replace issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionidissue-delete
  description: |-
    Deselects a select list issue field option in all issues that it has been selected in. A different option can be selected to replace the deselected option. The update can also be limited to a smaller set of issues by using a JQL query.

    This is an [asynchronous method](#async). The response object will contain a link to the long-running task. For example, _https://your-domain.atlassian.net/rest/api/2/task/10127_.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionidissue-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionidissue-delete-openapi.md
- name: Jira Cloud REST API - Create issue
  x-api-slug: api2issue-post
  description: |-
    Creates an issue or a sub-task from a JSON representation.

    You can provide two parameters in request's body: `update` or `fields`. The fields, that can be set on an issue create operation, can be determined using the **/rest/api/2/issue/createmeta** resource. If a particular field is not configured to appear on the issue's Create screen, then it will not be returned in the createmeta response. A field validation error will occur if such field is submitted in request.

    Creating a sub-task is similar to creating an issue with the following differences:

    *   `issueType` field must be set to a sub-task issue type (use `/issue/createmeta` to find sub-task issue types), and
    *   You must provide a `parent` field with the ID or key of the parent issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issue-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issue-post-openapi.md
- name: Jira Cloud REST API - Get create issue meta
  x-api-slug: api2issuecreatemeta-get
  description: |-
    Returns the metadata for creating issues. This includes the available projects, issue types, fields (with information whether those fields are required) and field types. Projects, in which the user does not have permission to create issues, will not be returned.

    The fields in the createmeta response correspond to the fields on the issue's Create screen for the specific project/issuetype. Fields hidden from the screen will not be returned in the createmeta response.

    Fields will only be returned if `expand=projects.issuetypes.fields` is set.

    The results can be filtered by project and/or issue type, controlled by the query parameters.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuecreatemeta-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuecreatemeta-get-openapi.md
- name: Jira Cloud REST API - Get issue picker resource
  x-api-slug: api2issuepicker-get
  description: Returns a list of suggested issues matching the auto-completion query
    for the user executing this request. This REST method checks the user's history
    and browsing context to return issue suggestions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuepicker-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuepicker-get-openapi.md
- name: Jira Cloud REST API - Bulk set issue property
  x-api-slug: api2issuepropertiespropertykey-put
  description: |-
    Allows to set a property for all issues identified by a given filter. Only entities the user has permissions to edit will be updated.

    Currently the following filters are available:

    *   **entityIds** \- A list of issues to update. Only issues with ids from this list will be considered for updating. This is an optional filter, if not provided, then any editable issue that matches all other filters will be updated.
    *   **currentValue** \- If provided, then only issues with the property currently set to that value will be updated.
    *   **hasProperty** \- If true, then only existing properties will be updated. If false, then only issues that do not have any value associated with this property will be updated. If omitted, the property will be set on all issues, regardless of whether it previously existed or not.

    If more than one filter is given, then they are all joined with the logical "and", that is: only issues that satisfy all filters are updated. If no filters are provided at all, then the property will be updated on _all_ issues editable by the caller (i.e. issues in projects with the EDIT_ISSUES permission).

    If an invalid combination of filters is provided, an error will be returned by the API. For example, specifying the current value and "hasProperty" to "false" would never match any issues (as it would mean: update this property if the current value is something, oh, but only if there is no value at all) and is therefore not allowed.

    This method is [asynchronous](#async), meaning that it will not return the results immediately, instead creating a task to perform the requested update operation (unless preliminary validation, e.g. of the provided filter, fails).

    The operation is transactional: either all eligible issues are updated, or none (if there are any errors).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuepropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuepropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Bulk delete issue property
  x-api-slug: api2issuepropertiespropertykey-delete
  description: Allows to delete a property from all issues identified by a given filter.
    Only entities the user has permissions to edit will be updated. See the [issue
    property bulk set endpoint documentation](#api-api-2-issue-properties-propertyKey-put)
    for more details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuepropertiespropertykey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuepropertiespropertykey-delete-openapi.md
- name: Jira Cloud REST API - Get issue
  x-api-slug: api2issueissueidorkey-get
  description: |-
    Returns a full representation of the issue for the given issue key.

    The issue JSON consists of the issue key and a collection of fields. Additional information like links to workflow transition sub-resources, or HTML rendered values of the fields supporting HTML rendering can be retrieved with `expand` request parameter specified.

    The `fields` request parameter accepts a comma-separated list of fields to include in the response. It can be used to retrieve a subset of fields. By default all fields are returned in the response. A particular field can be excluded from the response if prefixed with a "-" (minus) sign. Parameter can be provided multiple times on a single request.

    By default, all fields are returned in the response. Note: this is different from a JQL search - only navigable fields are returned by default (`*navigable`).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkey-get-openapi.md
- name: Jira Cloud REST API - Edit issue
  x-api-slug: api2issueissueidorkey-put
  description: "Edits the issue from a JSON representation.\n\nThe fields available
    for update can be determined using the **/rest/api/2/issue/{issueIdOrKey}/editmeta**
    resource.  \nIf a field is hidden from the Edit screen then it will not be returned
    by the editmeta resource. A field validation error will occur if such field is
    submitted in an edit request. However connect add-on with admin scope may override
    a screen security configuration.\n\nIf an issue cannot be edited in Jira because
    of its workflow status (for example the issue is closed), then you will not be
    able to edit it with this resource.\n\nField to be updated should appear either
    in `fields` or `update` request's body parameter, but not in both.  \nTo update
    a single sub-field of a complex field (e.g. timetracking) please use the `update`
    parameter of the edit operation. Using a `\"field_id\": field_value` construction
    in the `fields` parameter is a shortcut of \"set\" operation in the `update` parameter."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkey-put-openapi.md
- name: Jira Cloud REST API - Delete issue
  x-api-slug: api2issueissueidorkey-delete
  description: |-
    Deletes an individual issue.

    If the issue has sub-tasks you must set the `deleteSubtasks=true` parameter to delete the issue. You cannot delete an issue without deleting its sub-tasks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkey-delete-openapi.md
- name: Jira Cloud REST API - Assign issue
  x-api-slug: api2issueissueidorkeyassignee-put
  description: Assigns the issue to the user. Use this resource to assign issues for
    the users having "Assign Issue" permission, and not having the "Edit Issue" permission.
    If `name` body parameter is set to "-1" then automatic issue assignee is used.
    A `name` set to `null` will remove the assignee.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyassignee-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyassignee-put-openapi.md
- name: Jira Cloud REST API - Get edit issue meta
  x-api-slug: api2issueissueidorkeyeditmeta-get
  description: |-
    Returns the metadata for editing an issue.

    The fields returned by editmeta resource are the ones shown on the issue's Edit screen. Fields hidden from the screen will not be returned unless `overrideScreenSecurity` parameter is set to true.

    If an issue cannot be edited in Jira because of its workflow status (for example the issue is closed), then no fields will be returned, unless `overrideEditableFlag` is set to true.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyeditmeta-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyeditmeta-get-openapi.md
- name: Jira Cloud REST API - Get issue property keys
  x-api-slug: api2issueissueidorkeyproperties-get
  description: Returns the keys of all properties for the issue identified by the
    key or by the id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyproperties-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyproperties-get-openapi.md
- name: Jira Cloud REST API - Get issue property
  x-api-slug: api2issueissueidorkeypropertiespropertykey-get
  description: Returns the value of the property with a given key from the issue identified
    by the key or by the id. The user who retrieves the property is required to have
    permissions to read the issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeypropertiespropertykey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeypropertiespropertykey-get-openapi.md
- name: Jira Cloud REST API - Set issue property
  x-api-slug: api2issueissueidorkeypropertiespropertykey-put
  description: |-
    Sets the value of the specified issue's property.

    You can use this resource to store a custom data against the issue identified by the key or by the id. The user who stores the data is required to have permissions to edit the issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeypropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeypropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Delete issue property
  x-api-slug: api2issueissueidorkeypropertiespropertykey-delete
  description: Removes the property from the issue identified by the key or by the
    id. Ths user removing the property is required to have permissions to edit the
    issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeypropertiespropertykey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeypropertiespropertykey-delete-openapi.md
- name: Jira Cloud REST API - Get remote issue links
  x-api-slug: api2issueissueidorkeyremotelink-get
  description: Returns the remote issue links for the issue. This may be links to
    other Jira instances, web applications or web pages.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelink-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelink-get-openapi.md
- name: Jira Cloud REST API - Create or update remote issue link
  x-api-slug: api2issueissueidorkeyremotelink-post
  description: Creates or updates a remote issue link from a JSON representation.
    If a `globalId` is provided and a remote issue link exists with that globalId,
    the remote issue link is updated. Otherwise, the remote issue link is created.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelink-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelink-post-openapi.md
- name: Jira Cloud REST API - Delete remote issue link by global id
  x-api-slug: api2issueissueidorkeyremotelink-delete
  description: Deletes the issue's remote link with the given global ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelink-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelink-delete-openapi.md
- name: Jira Cloud REST API - Get remote issue link by id
  x-api-slug: api2issueissueidorkeyremotelinklinkid-get
  description: Returns the remote issue link by the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelinklinkid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelinklinkid-get-openapi.md
- name: Jira Cloud REST API - Update remote issue link
  x-api-slug: api2issueissueidorkeyremotelinklinkid-put
  description: Updates a remote issue link from a JSON representation. Sets all fields
    without values provided to null.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelinklinkid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelinklinkid-put-openapi.md
- name: Jira Cloud REST API - Delete remote issue link by id
  x-api-slug: api2issueissueidorkeyremotelinklinkid-delete
  description: Deletes the issue's remote link with the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelinklinkid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelinklinkid-delete-openapi.md
- name: Jira Cloud REST API - Get issue watchers
  x-api-slug: api2issueissueidorkeywatchers-get
  description: Returns the list of watchers for the issue with the given key.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeywatchers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeywatchers-get-openapi.md
- name: Jira Cloud REST API - Get issue worklog
  x-api-slug: api2issueissueidorkeyworklog-get
  description: "Returns all work logs for an issue. The response is [paginated](#pagination)
    \ \n**Note:** Work logs won't be returned if the Log work field is hidden for
    the project."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyworklog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyworklog-get-openapi.md
- name: Jira Cloud REST API - Get issue link
  x-api-slug: api2issuelinklinkid-get
  description: Returns an issue link with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinklinkid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinklinkid-get-openapi.md
- name: Jira Cloud REST API - Delete issue link
  x-api-slug: api2issuelinklinkid-delete
  description: Deletes an issue link with the specified id. To be able to delete an
    issue link you must be able to view both issues and must have the link issue permission
    for at least one of the issues.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinklinkid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinklinkid-delete-openapi.md
- name: Jira Cloud REST API - Get issue link types
  x-api-slug: api2issuelinktype-get
  description: Returns a list of available issue link types, if issue linking is enabled.
    Each issue link type has an id, a name and a label for the outward and inward
    link relationship.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktype-get-openapi.md
- name: Jira Cloud REST API - Create issue link type
  x-api-slug: api2issuelinktype-post
  description: Create a new issue link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktype-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktype-post-openapi.md
- name: Jira Cloud REST API - Get issue link type
  x-api-slug: api2issuelinktypeissuelinktypeid-get
  description: Returns for a given issue link type id all information about this issue
    link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-get-openapi.md
- name: Jira Cloud REST API - Update issue link type
  x-api-slug: api2issuelinktypeissuelinktypeid-put
  description: Update the specified issue link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-put-openapi.md
- name: Jira Cloud REST API - Delete issue link type
  x-api-slug: api2issuelinktypeissuelinktypeid-delete
  description: Delete the specified issue link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-delete-openapi.md
- name: Jira Cloud REST API - Get issue security schemes
  x-api-slug: api2issuesecurityschemes-get
  description: Returns all issue security schemes that are defined.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuesecurityschemes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuesecurityschemes-get-openapi.md
- name: Jira Cloud REST API - Get issue security scheme
  x-api-slug: api2issuesecurityschemesid-get
  description: Returns the issue security scheme along with that are defined.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuesecurityschemesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuesecurityschemesid-get-openapi.md
- name: Jira Cloud REST API - Get all issue types for user
  x-api-slug: api2issuetype-get
  description: Returns all issue types. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** Permission to access Jira, however, only issue types that are visible
    to the user are returned.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetype-get-openapi.md
- name: Jira Cloud REST API - Create issue type
  x-api-slug: api2issuetype-post
  description: Creates an issue type and adds it to the default issue type scheme.
    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer
    Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetype-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetype-post-openapi.md
- name: Jira Cloud REST API - Get issue type
  x-api-slug: api2issuetypeid-get
  description: |-
    Returns an issue type. [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:

    *   _Administer Jira_ [global permission](href=) to get the details of any issue type.
    *   _Browse projects_ project permission to get the details of any issue type associated with the projects the user has permission to browse.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeid-get-openapi.md
- name: Jira Cloud REST API - Update issue type
  x-api-slug: api2issuetypeid-put
  description: Updates the issue type. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeid-put-openapi.md
- name: Jira Cloud REST API - Delete issue type
  x-api-slug: api2issuetypeid-delete
  description: Deletes the issue type. If the issue type is in use, all uses are updated
    with the alternative issue type (`alternativeIssueTypeId`). A list of alternative
    issue types can be obtained from the [Get alternative issue types](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issuetype-id-alternatives-get)
    resource. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**
    _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeid-delete-openapi.md
- name: Jira Cloud REST API - Get alternative issue types
  x-api-slug: api2issuetypeidalternatives-get
  description: Returns a list of issue types that can be used to replace the issue
    type. The alternative issue types are those assigned to the same workflow scheme,
    field configuration scheme, and screen scheme. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeidalternatives-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeidalternatives-get-openapi.md
- name: Jira Cloud REST API - Create issue type avatar
  x-api-slug: api2issuetypeidavatar2-post
  description: |-
    Creates an avatar for the issue type. Specify the avatar's local file location as binary data in the body of the request. Also, include the following headers:

    *   `X-Atlassian-Token: no-check`
    *   `Content-Type: image/_image type_` Valid image types are JPEG, GIF, or PNG.

    For example: `curl --request POST \ --user email@example.com: \ --header 'X-Atlassian-Token: no-check' \ --header 'Content-Type: image/< image_type>' \ --data-binary "" \ --url 'https://your-domain.atlassian.net/rest/api/2/issuetype/{issueTypeId}'This` The avatar is cropped to a square. If no crop parameters are specified, the square originates at the top left of the image. The length of the square's sides is set to the smaller of the height or width of the image. The cropped image is then used to create avatars of 16x16, 24x24, 32x32, and 48x48 in size. After creating the avatar, use [Update issue type](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issuetype-id-put) to set it as the issue type's active avatar. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeidavatar2-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeidavatar2-post-openapi.md
- name: Jira Cloud REST API - Get issue type property keys
  x-api-slug: api2issuetypeissuetypeidproperties-get
  description: |-
    Returns all the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties) keys of the issue type. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**

    *   _Administer Jira_ [global permission](href=) to get the property keys of any issue type.
    *   _Browse projects_ project permission to get the property keys of any issue types associated with the projects the user has permission to browse.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidproperties-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidproperties-get-openapi.md
- name: Jira Cloud REST API - Get issue type property
  x-api-slug: api2issuetypeissuetypeidpropertiespropertykey-get
  description: |-
    Returns the key and value of the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties). [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:

    *   _Administer Jira_ [global permission](href=) to get the details of any issue type.
    *   _Browse projects_ project permission to get the details of any issue types associated with the projects the user has permission to browse.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-get-openapi.md
- name: Jira Cloud REST API - Set issue type property
  x-api-slug: api2issuetypeissuetypeidpropertiespropertykey-put
  description: Creates or updates the value of the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties).
    Use this resource to store and update data against an issue type. The value of
    the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty
    JSON blob. The maximum length of the property value is 32768 bytes. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Delete issue type property
  x-api-slug: api2issuetypeissuetypeidpropertiespropertykey-delete
  description: Deletes the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties).
    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer
    Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-delete-openapi.md
- name: Jira Cloud REST API - Get project issue security scheme
  x-api-slug: api2projectprojectkeyoridissuesecuritylevelscheme-get
  description: |-
    Returns the [issue security scheme](https://confluence.atlassian.com/x/J4lKLg) associated with the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or the _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2projectprojectkeyoridissuesecuritylevelscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2projectprojectkeyoridissuesecuritylevelscheme-get-openapi.md
- name: Jira Cloud REST API - Get project issue security levels
  x-api-slug: api2projectprojectkeyoridsecuritylevel-get
  description: |-
    Returns all [issue security](https://confluence.atlassian.com/x/J4lKLg) levels for the project that the currently authenticated user has access to. If the user does not have permission to see an issue security level, then that level is not returned. If the user lacks the _Set Issue Security_ permission, then an empty list is returned.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Set Issue Security_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2projectprojectkeyoridsecuritylevel-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2projectprojectkeyoridsecuritylevel-get-openapi.md
- name: Jira Cloud REST API - Get issue security level
  x-api-slug: api2securitylevelid-get
  description: Returns a full representation of the security level that has the given
    id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2securitylevelid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2securitylevelid-get-openapi.md
- name: Jira Cloud REST API - Get issue navigator default columns
  x-api-slug: api2settingscolumns-get
  description: Returns the default system columns for issue navigator. Admin permission
    will be required.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2settingscolumns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2settingscolumns-get-openapi.md
- name: Jira Cloud REST API - Set issue navigator default columns
  x-api-slug: api2settingscolumns-put
  description: Sets the default system columns for issue navigator. Admin permission
    will be required.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2settingscolumns-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2settingscolumns-put-openapi.md
- name: Jira Cloud REST API - Get workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-get
  description: Returns the issue type mapping for the passed draft workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Set workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed draft scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the draft scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Get workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-get
  description: Returns the issue type mapping for the passed workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Set workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Get component issues count
  x-api-slug: api2componentidrelatedissuecounts-get
  description: Returns the counts of issues assigned to the component. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2componentidrelatedissuecounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2componentidrelatedissuecounts-get-openapi.md
- name: Jira Cloud REST API - Create issues
  x-api-slug: api2issuebulk-post
  description: |-
    Creates multiple issues or sub-tasks from a JSON representation, in a single bulk operation.

    Creating a sub-task is similar to creating an issue - check Create issue section for details: {@link IssueResource#createIssue(boolean, IssueUpdateBean)}}
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuebulk-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuebulk-post-openapi.md
- name: Jira Cloud REST API - Get all permission schemes
  x-api-slug: api2permissionscheme-get
  description: |-
    Returns all permission schemes.

    ### About permission schemes and grants

    A permission scheme is a collection of permission grants. A permission grant consists of a `holder` and a `permission`.

    #### Holder

    The `holder` object contains information about the user or group being granted the permission. For example, the _Administer projects_ permission is granted to a group named _Teams in space administrators_. In this case, the type is `"type": "group"`, and the parameter is the group name, `"parameter": "Teams in space administrators"`. The `holder` object is defined by the following properties:

    *   `type` Identifies the user or group (see the list of types below).
    *   `parameter` The value of this property depends on the `type`. For example, if the `type` is a group, then you need to specify the group name.

    The following `types` are available. The expected values for the `parameter` are given in parenthesis (some `types` may not have a `parameter`):

    *   `anyone` Grant for anonymous users.
    *   `applicationRole` Grant for users with access to the specified application (application name). See [Manage application access](https://confluence.atlassian.com/cloud/manage-application-access-744721629.html) for more information.
    *   `assignee` Grant for the user currently assigned to an issue.
    *   `group` Grant for the specified group (group name).
    *   `groupCustomField` Grant for a user in the group selected in the specified custom field (custom field ID).
    *   `projectLead` Grant for a project lead.
    *   `projectRole` Grant for the specified project role (project role ID).
    *   `reporter` Grant for the user who reported the issue.
    *   `sd.customer.portal.only` Jira Service Desk only. Grants customers permission to access the customer portal but not Jira. See [Customizing Jira Service Desk permissions](https://confluence.atlassian.com/x/24dKLg) for more information.
    *   `user` Grant for the specified user (user ID).
    *   `userCustomField` Grant for a user selected in the specified custom field (custom field ID).

    #### Permissions

    The [built-in Jira permissions](https://confluence.atlassian.com/x/yodKLg) are listed below. Apps can also define custom permissions. See the [project permission](https://developer.atlassian.com/cloud/jira/platform/modules/project-permission/) and [global permission](https://developer.atlassian.com/cloud/jira/platform/modules/global-permission/) module documentation for more information.

    **Project permissions**

    *   `ADMINISTER_PROJECTS`
    *   `BROWSE_PROJECTS`
    *   `MANAGE_SPRINTS_PERMISSION` (Jira Software only)
    *   `SERVICEDESK_AGENT` (Jira Service Desk only)
    *   `VIEW_DEV_TOOLS` (Jira Software only)
    *   `VIEW_READONLY_WORKFLOW`

    **Issue permissions**

    *   `ASSIGNABLE_USER`
    *   `ASSIGN_ISSUES`
    *   `CLOSE_ISSUES`
    *   `CREATE_ISSUES`
    *   `DELETE_ISSUES`
    *   `EDIT_ISSUES`
    *   `LINK_ISSUES`
    *   `MODIFY_REPORTER`
    *   `MOVE_ISSUES`
    *   `RESOLVE_ISSUES`
    *   `SCHEDULE_ISSUES`
    *   `SET_ISSUE_SECURITY`
    *   `TRANSITION_ISSUES`

    **Voters and watchers permissions**

    *   `MANAGE_WATCHERS`
    *   `VIEW_VOTERS_AND_WATCHERS`

    **Comments permissions**

    *   `ADD_COMMENTS`
    *   `DELETE_ALL_COMMENTS`
    *   `DELETE_OWN_COMMENTS`
    *   `EDIT_ALL_COMMENTS`
    *   `EDIT_OWN_COMMENTS`

    **Attachments permissions**

    *   `CREATE_ATTACHMENTS`
    *   `DELETE_ALL_ATTACHMENTS`
    *   `DELETE_OWN_ATTACHMENTS`

    **Time tracking permissions**

    *   `DELETE_ALL_WORKLOGS`
    *   `DELETE_OWN_WORKLOGS`
    *   `EDIT_ALL_WORKLOGS`
    *   `EDIT_OWN_WORKLOGS`
    *   `WORK_ON_ISSUES`

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2permissionscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2permissionscheme-get-openapi.md
- name: Jira Cloud REST API - Merge versions
  x-api-slug: api2versionidmergetomoveissuesto-put
  description: Merges two project versions. The merge is completed by deleting the
    version specified in `id` and replacing any occurrences of its ID in `fixVersion`
    with the version ID specified in `moveIssuesTo`. Consider using [Delete and replace
    version](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-version-id-removeAndSwap-post)
    instead. This resource supports swapping version values in `fixVersion`, `affectedVersion`,
    and custom fields. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg)
    or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2versionidmergetomoveissuesto-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2versionidmergetomoveissuesto-put-openapi.md
- name: Jira Cloud REST API - Get version's related issues count
  x-api-slug: api2versionidrelatedissuecounts-get
  description: |-
    Returns the following counts for a version:

    *   Number of issues where the `fixVersion` is set to the version.
    *   Number of issues where the `affectedVersion` is set to the version.
    *   Number of issues where a version custom field is set to the version.

    [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required: _Browse projects_ project permission
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2versionidrelatedissuecounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2versionidrelatedissuecounts-get-openapi.md
- name: Jira Cloud REST API - Get version's unresolved issues count
  x-api-slug: api2versionidunresolvedissuecount-get
  description: 'Returns counts of the issues and unresolved issues for the project
    version. [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required: _Browse
    projects_ project permission'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2versionidunresolvedissuecount-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2versionidunresolvedissuecount-get-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Set workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Set workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Set workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Set workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Set workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Set workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Get workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-get
  description: Returns the issue type mapping for the passed workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Get workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-get
  description: Returns the issue type mapping for the passed workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Get workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-get
  description: Returns the issue type mapping for the passed workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Get workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-get
  description: Returns the issue type mapping for the passed workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Get workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-get
  description: Returns the issue type mapping for the passed workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Get workflow scheme issue type
  x-api-slug: api2workflowschemeidissuetypeissuetype-get
  description: Returns the issue type mapping for the passed workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeidissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the draft scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the draft scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the draft scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the draft scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Delete workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-delete
  description: Remove the specified issue type mapping from the draft scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-delete-openapi.md
- name: Jira Cloud REST API - Set workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed draft scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Set workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed draft scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Set workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed draft scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Set workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed draft scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Set workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed draft scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Set workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-put
  description: |-
    Set the issue type mapping for the passed draft scheme.

    The passed representation can have its updateDraftIfNeeded flag set to true to indicate that the draft should be created/updated when the actual scheme cannot be edited.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-put-openapi.md
- name: Jira Cloud REST API - Get workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-get
  description: Returns the issue type mapping for the passed draft workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Get workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-get
  description: Returns the issue type mapping for the passed draft workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Get workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-get
  description: Returns the issue type mapping for the passed draft workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Get workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-get
  description: Returns the issue type mapping for the passed draft workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Get workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-get
  description: Returns the issue type mapping for the passed draft workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Get workflow scheme draft issue type
  x-api-slug: api2workflowschemeiddraftissuetypeissuetype-get
  description: Returns the issue type mapping for the passed draft workflow scheme.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2workflowschemeiddraftissuetypeissuetype-get-openapi.md
- name: Jira Cloud REST API - Set issue navigator default columns
  x-api-slug: api2settingscolumns-put
  description: Sets the default system columns for issue navigator. Admin permission
    will be required.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2settingscolumns-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2settingscolumns-put-openapi.md
- name: Jira Cloud REST API - Set issue navigator default columns
  x-api-slug: api2settingscolumns-put
  description: Sets the default system columns for issue navigator. Admin permission
    will be required.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2settingscolumns-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2settingscolumns-put-openapi.md
- name: Jira Cloud REST API - Set issue navigator default columns
  x-api-slug: api2settingscolumns-put
  description: Sets the default system columns for issue navigator. Admin permission
    will be required.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2settingscolumns-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2settingscolumns-put-openapi.md
- name: Jira Cloud REST API - Get issue navigator default columns
  x-api-slug: api2settingscolumns-get
  description: Returns the default system columns for issue navigator. Admin permission
    will be required.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2settingscolumns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2settingscolumns-get-openapi.md
- name: Jira Cloud REST API - Get issue navigator default columns
  x-api-slug: api2settingscolumns-get
  description: Returns the default system columns for issue navigator. Admin permission
    will be required.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2settingscolumns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2settingscolumns-get-openapi.md
- name: Jira Cloud REST API - Get issue security level
  x-api-slug: api2securitylevelid-get
  description: Returns a full representation of the security level that has the given
    id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2securitylevelid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2securitylevelid-get-openapi.md
- name: Jira Cloud REST API - Get project issue security levels
  x-api-slug: api2projectprojectkeyoridsecuritylevel-get
  description: |-
    Returns all [issue security](https://confluence.atlassian.com/x/J4lKLg) levels for the project that the currently authenticated user has access to. If the user does not have permission to see an issue security level, then that level is not returned. If the user lacks the _Set Issue Security_ permission, then an empty list is returned.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Set Issue Security_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2projectprojectkeyoridsecuritylevel-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2projectprojectkeyoridsecuritylevel-get-openapi.md
- name: Jira Cloud REST API - Get project issue security levels
  x-api-slug: api2projectprojectkeyoridsecuritylevel-get
  description: |-
    Returns all [issue security](https://confluence.atlassian.com/x/J4lKLg) levels for the project that the currently authenticated user has access to. If the user does not have permission to see an issue security level, then that level is not returned. If the user lacks the _Set Issue Security_ permission, then an empty list is returned.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Set Issue Security_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2projectprojectkeyoridsecuritylevel-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2projectprojectkeyoridsecuritylevel-get-openapi.md
- name: Jira Cloud REST API - Get project issue security levels
  x-api-slug: api2projectprojectkeyoridsecuritylevel-get
  description: |-
    Returns all [issue security](https://confluence.atlassian.com/x/J4lKLg) levels for the project that the currently authenticated user has access to. If the user does not have permission to see an issue security level, then that level is not returned. If the user lacks the _Set Issue Security_ permission, then an empty list is returned.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Set Issue Security_ [global permission](https://confluence.atlassian.com/x/x4dKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2projectprojectkeyoridsecuritylevel-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2projectprojectkeyoridsecuritylevel-get-openapi.md
- name: Jira Cloud REST API - Get project issue security scheme
  x-api-slug: api2projectprojectkeyoridissuesecuritylevelscheme-get
  description: |-
    Returns the [issue security scheme](https://confluence.atlassian.com/x/J4lKLg) associated with the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or the _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2projectprojectkeyoridissuesecuritylevelscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2projectprojectkeyoridissuesecuritylevelscheme-get-openapi.md
- name: Jira Cloud REST API - Get project issue security scheme
  x-api-slug: api2projectprojectkeyoridissuesecuritylevelscheme-get
  description: |-
    Returns the [issue security scheme](https://confluence.atlassian.com/x/J4lKLg) associated with the project.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or the _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2projectprojectkeyoridissuesecuritylevelscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2projectprojectkeyoridissuesecuritylevelscheme-get-openapi.md
- name: Jira Cloud REST API - Delete issue type property
  x-api-slug: api2issuetypeissuetypeidpropertiespropertykey-delete
  description: Deletes the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties).
    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer
    Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-delete-openapi.md
- name: Jira Cloud REST API - Delete issue type property
  x-api-slug: api2issuetypeissuetypeidpropertiespropertykey-delete
  description: Deletes the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties).
    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer
    Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-delete-openapi.md
- name: Jira Cloud REST API - Set issue type property
  x-api-slug: api2issuetypeissuetypeidpropertiespropertykey-put
  description: Creates or updates the value of the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties).
    Use this resource to store and update data against an issue type. The value of
    the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty
    JSON blob. The maximum length of the property value is 32768 bytes. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Set issue type property
  x-api-slug: api2issuetypeissuetypeidpropertiespropertykey-put
  description: Creates or updates the value of the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties).
    Use this resource to store and update data against an issue type. The value of
    the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty
    JSON blob. The maximum length of the property value is 32768 bytes. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Get issue type property
  x-api-slug: api2issuetypeissuetypeidpropertiespropertykey-get
  description: |-
    Returns the key and value of the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties). [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:

    *   _Administer Jira_ [global permission](href=) to get the details of any issue type.
    *   _Browse projects_ project permission to get the details of any issue types associated with the projects the user has permission to browse.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-get-openapi.md
- name: Jira Cloud REST API - Get issue type property
  x-api-slug: api2issuetypeissuetypeidpropertiespropertykey-get
  description: |-
    Returns the key and value of the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties). [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:

    *   _Administer Jira_ [global permission](href=) to get the details of any issue type.
    *   _Browse projects_ project permission to get the details of any issue types associated with the projects the user has permission to browse.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidpropertiespropertykey-get-openapi.md
- name: Jira Cloud REST API - Get issue type property keys
  x-api-slug: api2issuetypeissuetypeidproperties-get
  description: |-
    Returns all the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties) keys of the issue type. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**

    *   _Administer Jira_ [global permission](href=) to get the property keys of any issue type.
    *   _Browse projects_ project permission to get the property keys of any issue types associated with the projects the user has permission to browse.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidproperties-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidproperties-get-openapi.md
- name: Jira Cloud REST API - Get issue type property keys
  x-api-slug: api2issuetypeissuetypeidproperties-get
  description: |-
    Returns all the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties) keys of the issue type. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**

    *   _Administer Jira_ [global permission](href=) to get the property keys of any issue type.
    *   _Browse projects_ project permission to get the property keys of any issue types associated with the projects the user has permission to browse.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidproperties-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeissuetypeidproperties-get-openapi.md
- name: Jira Cloud REST API - Create issue type avatar
  x-api-slug: api2issuetypeidavatar2-post
  description: |-
    Creates an avatar for the issue type. Specify the avatar's local file location as binary data in the body of the request. Also, include the following headers:

    *   `X-Atlassian-Token: no-check`
    *   `Content-Type: image/_image type_` Valid image types are JPEG, GIF, or PNG.

    For example: `curl --request POST \ --user email@example.com: \ --header 'X-Atlassian-Token: no-check' \ --header 'Content-Type: image/< image_type>' \ --data-binary "" \ --url 'https://your-domain.atlassian.net/rest/api/2/issuetype/{issueTypeId}'This` The avatar is cropped to a square. If no crop parameters are specified, the square originates at the top left of the image. The length of the square's sides is set to the smaller of the height or width of the image. The cropped image is then used to create avatars of 16x16, 24x24, 32x32, and 48x48 in size. After creating the avatar, use [Update issue type](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issuetype-id-put) to set it as the issue type's active avatar. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeidavatar2-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeidavatar2-post-openapi.md
- name: Jira Cloud REST API - Create issue type avatar
  x-api-slug: api2issuetypeidavatar2-post
  description: |-
    Creates an avatar for the issue type. Specify the avatar's local file location as binary data in the body of the request. Also, include the following headers:

    *   `X-Atlassian-Token: no-check`
    *   `Content-Type: image/_image type_` Valid image types are JPEG, GIF, or PNG.

    For example: `curl --request POST \ --user email@example.com: \ --header 'X-Atlassian-Token: no-check' \ --header 'Content-Type: image/< image_type>' \ --data-binary "" \ --url 'https://your-domain.atlassian.net/rest/api/2/issuetype/{issueTypeId}'This` The avatar is cropped to a square. If no crop parameters are specified, the square originates at the top left of the image. The length of the square's sides is set to the smaller of the height or width of the image. The cropped image is then used to create avatars of 16x16, 24x24, 32x32, and 48x48 in size. After creating the avatar, use [Update issue type](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issuetype-id-put) to set it as the issue type's active avatar. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeidavatar2-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeidavatar2-post-openapi.md
- name: Jira Cloud REST API - Get alternative issue types
  x-api-slug: api2issuetypeidalternatives-get
  description: Returns a list of issue types that can be used to replace the issue
    type. The alternative issue types are those assigned to the same workflow scheme,
    field configuration scheme, and screen scheme. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeidalternatives-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeidalternatives-get-openapi.md
- name: Jira Cloud REST API - Get alternative issue types
  x-api-slug: api2issuetypeidalternatives-get
  description: Returns a list of issue types that can be used to replace the issue
    type. The alternative issue types are those assigned to the same workflow scheme,
    field configuration scheme, and screen scheme. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeidalternatives-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeidalternatives-get-openapi.md
- name: Jira Cloud REST API - Delete issue type
  x-api-slug: api2issuetypeid-delete
  description: Deletes the issue type. If the issue type is in use, all uses are updated
    with the alternative issue type (`alternativeIssueTypeId`). A list of alternative
    issue types can be obtained from the [Get alternative issue types](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issuetype-id-alternatives-get)
    resource. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**
    _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeid-delete-openapi.md
- name: Jira Cloud REST API - Delete issue type
  x-api-slug: api2issuetypeid-delete
  description: Deletes the issue type. If the issue type is in use, all uses are updated
    with the alternative issue type (`alternativeIssueTypeId`). A list of alternative
    issue types can be obtained from the [Get alternative issue types](https://developer.atlassian.com/cloud/jira/platform/rest/#api-api-2-issuetype-id-alternatives-get)
    resource. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**
    _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeid-delete-openapi.md
- name: Jira Cloud REST API - Update issue type
  x-api-slug: api2issuetypeid-put
  description: Updates the issue type. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeid-put-openapi.md
- name: Jira Cloud REST API - Update issue type
  x-api-slug: api2issuetypeid-put
  description: Updates the issue type. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** _Administer Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeid-put-openapi.md
- name: Jira Cloud REST API - Get issue type
  x-api-slug: api2issuetypeid-get
  description: |-
    Returns an issue type. [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:

    *   _Administer Jira_ [global permission](href=) to get the details of any issue type.
    *   _Browse projects_ project permission to get the details of any issue type associated with the projects the user has permission to browse.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeid-get-openapi.md
- name: Jira Cloud REST API - Get issue type
  x-api-slug: api2issuetypeid-get
  description: |-
    Returns an issue type. [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:

    *   _Administer Jira_ [global permission](href=) to get the details of any issue type.
    *   _Browse projects_ project permission to get the details of any issue type associated with the projects the user has permission to browse.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetypeid-get-openapi.md
- name: Jira Cloud REST API - Create issue type
  x-api-slug: api2issuetype-post
  description: Creates an issue type and adds it to the default issue type scheme.
    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer
    Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetype-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetype-post-openapi.md
- name: Jira Cloud REST API - Create issue type
  x-api-slug: api2issuetype-post
  description: Creates an issue type and adds it to the default issue type scheme.
    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer
    Jira_ [global permission](href=).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetype-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetype-post-openapi.md
- name: Jira Cloud REST API - Get all issue types for user
  x-api-slug: api2issuetype-get
  description: Returns all issue types. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** Permission to access Jira, however, only issue types that are visible
    to the user are returned.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetype-get-openapi.md
- name: Jira Cloud REST API - Get all issue types for user
  x-api-slug: api2issuetype-get
  description: Returns all issue types. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
    required:** Permission to access Jira, however, only issue types that are visible
    to the user are returned.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuetype-get-openapi.md
- name: Jira Cloud REST API - Get issue security scheme
  x-api-slug: api2issuesecurityschemesid-get
  description: Returns the issue security scheme along with that are defined.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuesecurityschemesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuesecurityschemesid-get-openapi.md
- name: Jira Cloud REST API - Get issue security scheme
  x-api-slug: api2issuesecurityschemesid-get
  description: Returns the issue security scheme along with that are defined.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuesecurityschemesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuesecurityschemesid-get-openapi.md
- name: Jira Cloud REST API - Get issue security schemes
  x-api-slug: api2issuesecurityschemes-get
  description: Returns all issue security schemes that are defined.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuesecurityschemes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuesecurityschemes-get-openapi.md
- name: Jira Cloud REST API - Get issue security schemes
  x-api-slug: api2issuesecurityschemes-get
  description: Returns all issue security schemes that are defined.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuesecurityschemes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuesecurityschemes-get-openapi.md
- name: Jira Cloud REST API - Delete issue link type
  x-api-slug: api2issuelinktypeissuelinktypeid-delete
  description: Delete the specified issue link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-delete-openapi.md
- name: Jira Cloud REST API - Delete issue link type
  x-api-slug: api2issuelinktypeissuelinktypeid-delete
  description: Delete the specified issue link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-delete-openapi.md
- name: Jira Cloud REST API - Update issue link type
  x-api-slug: api2issuelinktypeissuelinktypeid-put
  description: Update the specified issue link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-put-openapi.md
- name: Jira Cloud REST API - Update issue link type
  x-api-slug: api2issuelinktypeissuelinktypeid-put
  description: Update the specified issue link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-put-openapi.md
- name: Jira Cloud REST API - Get issue link type
  x-api-slug: api2issuelinktypeissuelinktypeid-get
  description: Returns for a given issue link type id all information about this issue
    link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-get-openapi.md
- name: Jira Cloud REST API - Get issue link type
  x-api-slug: api2issuelinktypeissuelinktypeid-get
  description: Returns for a given issue link type id all information about this issue
    link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktypeissuelinktypeid-get-openapi.md
- name: Jira Cloud REST API - Create issue link type
  x-api-slug: api2issuelinktype-post
  description: Create a new issue link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktype-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktype-post-openapi.md
- name: Jira Cloud REST API - Create issue link type
  x-api-slug: api2issuelinktype-post
  description: Create a new issue link type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktype-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktype-post-openapi.md
- name: Jira Cloud REST API - Get issue link types
  x-api-slug: api2issuelinktype-get
  description: Returns a list of available issue link types, if issue linking is enabled.
    Each issue link type has an id, a name and a label for the outward and inward
    link relationship.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktype-get-openapi.md
- name: Jira Cloud REST API - Get issue link types
  x-api-slug: api2issuelinktype-get
  description: Returns a list of available issue link types, if issue linking is enabled.
    Each issue link type has an id, a name and a label for the outward and inward
    link relationship.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinktype-get-openapi.md
- name: Jira Cloud REST API - Delete issue link
  x-api-slug: api2issuelinklinkid-delete
  description: Deletes an issue link with the specified id. To be able to delete an
    issue link you must be able to view both issues and must have the link issue permission
    for at least one of the issues.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinklinkid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinklinkid-delete-openapi.md
- name: Jira Cloud REST API - Delete issue link
  x-api-slug: api2issuelinklinkid-delete
  description: Deletes an issue link with the specified id. To be able to delete an
    issue link you must be able to view both issues and must have the link issue permission
    for at least one of the issues.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinklinkid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinklinkid-delete-openapi.md
- name: Jira Cloud REST API - Get issue link
  x-api-slug: api2issuelinklinkid-get
  description: Returns an issue link with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinklinkid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinklinkid-get-openapi.md
- name: Jira Cloud REST API - Get issue link
  x-api-slug: api2issuelinklinkid-get
  description: Returns an issue link with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinklinkid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuelinklinkid-get-openapi.md
- name: Jira Cloud REST API - Get issue worklog
  x-api-slug: api2issueissueidorkeyworklog-get
  description: "Returns all work logs for an issue. The response is [paginated](#pagination)
    \ \n**Note:** Work logs won't be returned if the Log work field is hidden for
    the project."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyworklog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyworklog-get-openapi.md
- name: Jira Cloud REST API - Get issue worklog
  x-api-slug: api2issueissueidorkeyworklog-get
  description: "Returns all work logs for an issue. The response is [paginated](#pagination)
    \ \n**Note:** Work logs won't be returned if the Log work field is hidden for
    the project."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyworklog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyworklog-get-openapi.md
- name: Jira Cloud REST API - Get issue watchers
  x-api-slug: api2issueissueidorkeywatchers-get
  description: Returns the list of watchers for the issue with the given key.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeywatchers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeywatchers-get-openapi.md
- name: Jira Cloud REST API - Get issue watchers
  x-api-slug: api2issueissueidorkeywatchers-get
  description: Returns the list of watchers for the issue with the given key.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeywatchers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeywatchers-get-openapi.md
- name: Jira Cloud REST API - Delete remote issue link by id
  x-api-slug: api2issueissueidorkeyremotelinklinkid-delete
  description: Deletes the issue's remote link with the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelinklinkid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelinklinkid-delete-openapi.md
- name: Jira Cloud REST API - Delete remote issue link by id
  x-api-slug: api2issueissueidorkeyremotelinklinkid-delete
  description: Deletes the issue's remote link with the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelinklinkid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelinklinkid-delete-openapi.md
- name: Jira Cloud REST API - Update remote issue link
  x-api-slug: api2issueissueidorkeyremotelinklinkid-put
  description: Updates a remote issue link from a JSON representation. Sets all fields
    without values provided to null.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelinklinkid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelinklinkid-put-openapi.md
- name: Jira Cloud REST API - Update remote issue link
  x-api-slug: api2issueissueidorkeyremotelinklinkid-put
  description: Updates a remote issue link from a JSON representation. Sets all fields
    without values provided to null.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelinklinkid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelinklinkid-put-openapi.md
- name: Jira Cloud REST API - Get remote issue link by id
  x-api-slug: api2issueissueidorkeyremotelinklinkid-get
  description: Returns the remote issue link by the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelinklinkid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelinklinkid-get-openapi.md
- name: Jira Cloud REST API - Get remote issue link by id
  x-api-slug: api2issueissueidorkeyremotelinklinkid-get
  description: Returns the remote issue link by the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelinklinkid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelinklinkid-get-openapi.md
- name: Jira Cloud REST API - Delete remote issue link by global id
  x-api-slug: api2issueissueidorkeyremotelink-delete
  description: Deletes the issue's remote link with the given global ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelink-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelink-delete-openapi.md
- name: Jira Cloud REST API - Delete remote issue link by global id
  x-api-slug: api2issueissueidorkeyremotelink-delete
  description: Deletes the issue's remote link with the given global ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelink-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelink-delete-openapi.md
- name: Jira Cloud REST API - Create or update remote issue link
  x-api-slug: api2issueissueidorkeyremotelink-post
  description: Creates or updates a remote issue link from a JSON representation.
    If a `globalId` is provided and a remote issue link exists with that globalId,
    the remote issue link is updated. Otherwise, the remote issue link is created.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelink-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelink-post-openapi.md
- name: Jira Cloud REST API - Create or update remote issue link
  x-api-slug: api2issueissueidorkeyremotelink-post
  description: Creates or updates a remote issue link from a JSON representation.
    If a `globalId` is provided and a remote issue link exists with that globalId,
    the remote issue link is updated. Otherwise, the remote issue link is created.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelink-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelink-post-openapi.md
- name: Jira Cloud REST API - Get remote issue links
  x-api-slug: api2issueissueidorkeyremotelink-get
  description: Returns the remote issue links for the issue. This may be links to
    other Jira instances, web applications or web pages.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelink-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelink-get-openapi.md
- name: Jira Cloud REST API - Get remote issue links
  x-api-slug: api2issueissueidorkeyremotelink-get
  description: Returns the remote issue links for the issue. This may be links to
    other Jira instances, web applications or web pages.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelink-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyremotelink-get-openapi.md
- name: Jira Cloud REST API - Delete issue property
  x-api-slug: api2issueissueidorkeypropertiespropertykey-delete
  description: Removes the property from the issue identified by the key or by the
    id. Ths user removing the property is required to have permissions to edit the
    issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeypropertiespropertykey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeypropertiespropertykey-delete-openapi.md
- name: Jira Cloud REST API - Delete issue property
  x-api-slug: api2issueissueidorkeypropertiespropertykey-delete
  description: Removes the property from the issue identified by the key or by the
    id. Ths user removing the property is required to have permissions to edit the
    issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeypropertiespropertykey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeypropertiespropertykey-delete-openapi.md
- name: Jira Cloud REST API - Set issue property
  x-api-slug: api2issueissueidorkeypropertiespropertykey-put
  description: |-
    Sets the value of the specified issue's property.

    You can use this resource to store a custom data against the issue identified by the key or by the id. The user who stores the data is required to have permissions to edit the issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeypropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeypropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Set issue property
  x-api-slug: api2issueissueidorkeypropertiespropertykey-put
  description: |-
    Sets the value of the specified issue's property.

    You can use this resource to store a custom data against the issue identified by the key or by the id. The user who stores the data is required to have permissions to edit the issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeypropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeypropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Get issue property
  x-api-slug: api2issueissueidorkeypropertiespropertykey-get
  description: Returns the value of the property with a given key from the issue identified
    by the key or by the id. The user who retrieves the property is required to have
    permissions to read the issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeypropertiespropertykey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeypropertiespropertykey-get-openapi.md
- name: Jira Cloud REST API - Get issue property
  x-api-slug: api2issueissueidorkeypropertiespropertykey-get
  description: Returns the value of the property with a given key from the issue identified
    by the key or by the id. The user who retrieves the property is required to have
    permissions to read the issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeypropertiespropertykey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeypropertiespropertykey-get-openapi.md
- name: Jira Cloud REST API - Get issue property keys
  x-api-slug: api2issueissueidorkeyproperties-get
  description: Returns the keys of all properties for the issue identified by the
    key or by the id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyproperties-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyproperties-get-openapi.md
- name: Jira Cloud REST API - Get issue property keys
  x-api-slug: api2issueissueidorkeyproperties-get
  description: Returns the keys of all properties for the issue identified by the
    key or by the id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyproperties-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyproperties-get-openapi.md
- name: Jira Cloud REST API - Get edit issue meta
  x-api-slug: api2issueissueidorkeyeditmeta-get
  description: |-
    Returns the metadata for editing an issue.

    The fields returned by editmeta resource are the ones shown on the issue's Edit screen. Fields hidden from the screen will not be returned unless `overrideScreenSecurity` parameter is set to true.

    If an issue cannot be edited in Jira because of its workflow status (for example the issue is closed), then no fields will be returned, unless `overrideEditableFlag` is set to true.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyeditmeta-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyeditmeta-get-openapi.md
- name: Jira Cloud REST API - Get edit issue meta
  x-api-slug: api2issueissueidorkeyeditmeta-get
  description: |-
    Returns the metadata for editing an issue.

    The fields returned by editmeta resource are the ones shown on the issue's Edit screen. Fields hidden from the screen will not be returned unless `overrideScreenSecurity` parameter is set to true.

    If an issue cannot be edited in Jira because of its workflow status (for example the issue is closed), then no fields will be returned, unless `overrideEditableFlag` is set to true.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyeditmeta-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyeditmeta-get-openapi.md
- name: Jira Cloud REST API - Assign issue
  x-api-slug: api2issueissueidorkeyassignee-put
  description: Assigns the issue to the user. Use this resource to assign issues for
    the users having "Assign Issue" permission, and not having the "Edit Issue" permission.
    If `name` body parameter is set to "-1" then automatic issue assignee is used.
    A `name` set to `null` will remove the assignee.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyassignee-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyassignee-put-openapi.md
- name: Jira Cloud REST API - Assign issue
  x-api-slug: api2issueissueidorkeyassignee-put
  description: Assigns the issue to the user. Use this resource to assign issues for
    the users having "Assign Issue" permission, and not having the "Edit Issue" permission.
    If `name` body parameter is set to "-1" then automatic issue assignee is used.
    A `name` set to `null` will remove the assignee.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyassignee-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkeyassignee-put-openapi.md
- name: Jira Cloud REST API - Delete issue
  x-api-slug: api2issueissueidorkey-delete
  description: |-
    Deletes an individual issue.

    If the issue has sub-tasks you must set the `deleteSubtasks=true` parameter to delete the issue. You cannot delete an issue without deleting its sub-tasks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkey-delete-openapi.md
- name: Jira Cloud REST API - Delete issue
  x-api-slug: api2issueissueidorkey-delete
  description: |-
    Deletes an individual issue.

    If the issue has sub-tasks you must set the `deleteSubtasks=true` parameter to delete the issue. You cannot delete an issue without deleting its sub-tasks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkey-delete-openapi.md
- name: Jira Cloud REST API - Edit issue
  x-api-slug: api2issueissueidorkey-put
  description: "Edits the issue from a JSON representation.\n\nThe fields available
    for update can be determined using the **/rest/api/2/issue/{issueIdOrKey}/editmeta**
    resource.  \nIf a field is hidden from the Edit screen then it will not be returned
    by the editmeta resource. A field validation error will occur if such field is
    submitted in an edit request. However connect add-on with admin scope may override
    a screen security configuration.\n\nIf an issue cannot be edited in Jira because
    of its workflow status (for example the issue is closed), then you will not be
    able to edit it with this resource.\n\nField to be updated should appear either
    in `fields` or `update` request's body parameter, but not in both.  \nTo update
    a single sub-field of a complex field (e.g. timetracking) please use the `update`
    parameter of the edit operation. Using a `\"field_id\": field_value` construction
    in the `fields` parameter is a shortcut of \"set\" operation in the `update` parameter."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkey-put-openapi.md
- name: Jira Cloud REST API - Edit issue
  x-api-slug: api2issueissueidorkey-put
  description: "Edits the issue from a JSON representation.\n\nThe fields available
    for update can be determined using the **/rest/api/2/issue/{issueIdOrKey}/editmeta**
    resource.  \nIf a field is hidden from the Edit screen then it will not be returned
    by the editmeta resource. A field validation error will occur if such field is
    submitted in an edit request. However connect add-on with admin scope may override
    a screen security configuration.\n\nIf an issue cannot be edited in Jira because
    of its workflow status (for example the issue is closed), then you will not be
    able to edit it with this resource.\n\nField to be updated should appear either
    in `fields` or `update` request's body parameter, but not in both.  \nTo update
    a single sub-field of a complex field (e.g. timetracking) please use the `update`
    parameter of the edit operation. Using a `\"field_id\": field_value` construction
    in the `fields` parameter is a shortcut of \"set\" operation in the `update` parameter."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkey-put-openapi.md
- name: Jira Cloud REST API - Get issue
  x-api-slug: api2issueissueidorkey-get
  description: |-
    Returns a full representation of the issue for the given issue key.

    The issue JSON consists of the issue key and a collection of fields. Additional information like links to workflow transition sub-resources, or HTML rendered values of the fields supporting HTML rendering can be retrieved with `expand` request parameter specified.

    The `fields` request parameter accepts a comma-separated list of fields to include in the response. It can be used to retrieve a subset of fields. By default all fields are returned in the response. A particular field can be excluded from the response if prefixed with a "-" (minus) sign. Parameter can be provided multiple times on a single request.

    By default, all fields are returned in the response. Note: this is different from a JQL search - only navigable fields are returned by default (`*navigable`).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkey-get-openapi.md
- name: Jira Cloud REST API - Get issue
  x-api-slug: api2issueissueidorkey-get
  description: |-
    Returns a full representation of the issue for the given issue key.

    The issue JSON consists of the issue key and a collection of fields. Additional information like links to workflow transition sub-resources, or HTML rendered values of the fields supporting HTML rendering can be retrieved with `expand` request parameter specified.

    The `fields` request parameter accepts a comma-separated list of fields to include in the response. It can be used to retrieve a subset of fields. By default all fields are returned in the response. A particular field can be excluded from the response if prefixed with a "-" (minus) sign. Parameter can be provided multiple times on a single request.

    By default, all fields are returned in the response. Note: this is different from a JQL search - only navigable fields are returned by default (`*navigable`).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issueissueidorkey-get-openapi.md
- name: Jira Cloud REST API - Bulk delete issue property
  x-api-slug: api2issuepropertiespropertykey-delete
  description: Allows to delete a property from all issues identified by a given filter.
    Only entities the user has permissions to edit will be updated. See the [issue
    property bulk set endpoint documentation](#api-api-2-issue-properties-propertyKey-put)
    for more details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuepropertiespropertykey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuepropertiespropertykey-delete-openapi.md
- name: Jira Cloud REST API - Bulk delete issue property
  x-api-slug: api2issuepropertiespropertykey-delete
  description: Allows to delete a property from all issues identified by a given filter.
    Only entities the user has permissions to edit will be updated. See the [issue
    property bulk set endpoint documentation](#api-api-2-issue-properties-propertyKey-put)
    for more details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuepropertiespropertykey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuepropertiespropertykey-delete-openapi.md
- name: Jira Cloud REST API - Bulk set issue property
  x-api-slug: api2issuepropertiespropertykey-put
  description: |-
    Allows to set a property for all issues identified by a given filter. Only entities the user has permissions to edit will be updated.

    Currently the following filters are available:

    *   **entityIds** \- A list of issues to update. Only issues with ids from this list will be considered for updating. This is an optional filter, if not provided, then any editable issue that matches all other filters will be updated.
    *   **currentValue** \- If provided, then only issues with the property currently set to that value will be updated.
    *   **hasProperty** \- If true, then only existing properties will be updated. If false, then only issues that do not have any value associated with this property will be updated. If omitted, the property will be set on all issues, regardless of whether it previously existed or not.

    If more than one filter is given, then they are all joined with the logical "and", that is: only issues that satisfy all filters are updated. If no filters are provided at all, then the property will be updated on _all_ issues editable by the caller (i.e. issues in projects with the EDIT_ISSUES permission).

    If an invalid combination of filters is provided, an error will be returned by the API. For example, specifying the current value and "hasProperty" to "false" would never match any issues (as it would mean: update this property if the current value is something, oh, but only if there is no value at all) and is therefore not allowed.

    This method is [asynchronous](#async), meaning that it will not return the results immediately, instead creating a task to perform the requested update operation (unless preliminary validation, e.g. of the provided filter, fails).

    The operation is transactional: either all eligible issues are updated, or none (if there are any errors).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuepropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuepropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Bulk set issue property
  x-api-slug: api2issuepropertiespropertykey-put
  description: |-
    Allows to set a property for all issues identified by a given filter. Only entities the user has permissions to edit will be updated.

    Currently the following filters are available:

    *   **entityIds** \- A list of issues to update. Only issues with ids from this list will be considered for updating. This is an optional filter, if not provided, then any editable issue that matches all other filters will be updated.
    *   **currentValue** \- If provided, then only issues with the property currently set to that value will be updated.
    *   **hasProperty** \- If true, then only existing properties will be updated. If false, then only issues that do not have any value associated with this property will be updated. If omitted, the property will be set on all issues, regardless of whether it previously existed or not.

    If more than one filter is given, then they are all joined with the logical "and", that is: only issues that satisfy all filters are updated. If no filters are provided at all, then the property will be updated on _all_ issues editable by the caller (i.e. issues in projects with the EDIT_ISSUES permission).

    If an invalid combination of filters is provided, an error will be returned by the API. For example, specifying the current value and "hasProperty" to "false" would never match any issues (as it would mean: update this property if the current value is something, oh, but only if there is no value at all) and is therefore not allowed.

    This method is [asynchronous](#async), meaning that it will not return the results immediately, instead creating a task to perform the requested update operation (unless preliminary validation, e.g. of the provided filter, fails).

    The operation is transactional: either all eligible issues are updated, or none (if there are any errors).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuepropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuepropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Get issue picker resource
  x-api-slug: api2issuepicker-get
  description: Returns a list of suggested issues matching the auto-completion query
    for the user executing this request. This REST method checks the user's history
    and browsing context to return issue suggestions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuepicker-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuepicker-get-openapi.md
- name: Jira Cloud REST API - Get issue picker resource
  x-api-slug: api2issuepicker-get
  description: Returns a list of suggested issues matching the auto-completion query
    for the user executing this request. This REST method checks the user's history
    and browsing context to return issue suggestions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuepicker-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuepicker-get-openapi.md
- name: Jira Cloud REST API - Get create issue meta
  x-api-slug: api2issuecreatemeta-get
  description: |-
    Returns the metadata for creating issues. This includes the available projects, issue types, fields (with information whether those fields are required) and field types. Projects, in which the user does not have permission to create issues, will not be returned.

    The fields in the createmeta response correspond to the fields on the issue's Create screen for the specific project/issuetype. Fields hidden from the screen will not be returned in the createmeta response.

    Fields will only be returned if `expand=projects.issuetypes.fields` is set.

    The results can be filtered by project and/or issue type, controlled by the query parameters.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuecreatemeta-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuecreatemeta-get-openapi.md
- name: Jira Cloud REST API - Get create issue meta
  x-api-slug: api2issuecreatemeta-get
  description: |-
    Returns the metadata for creating issues. This includes the available projects, issue types, fields (with information whether those fields are required) and field types. Projects, in which the user does not have permission to create issues, will not be returned.

    The fields in the createmeta response correspond to the fields on the issue's Create screen for the specific project/issuetype. Fields hidden from the screen will not be returned in the createmeta response.

    Fields will only be returned if `expand=projects.issuetypes.fields` is set.

    The results can be filtered by project and/or issue type, controlled by the query parameters.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuecreatemeta-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issuecreatemeta-get-openapi.md
- name: Jira Cloud REST API - Create issue
  x-api-slug: api2issue-post
  description: |-
    Creates an issue or a sub-task from a JSON representation.

    You can provide two parameters in request's body: `update` or `fields`. The fields, that can be set on an issue create operation, can be determined using the **/rest/api/2/issue/createmeta** resource. If a particular field is not configured to appear on the issue's Create screen, then it will not be returned in the createmeta response. A field validation error will occur if such field is submitted in request.

    Creating a sub-task is similar to creating an issue with the following differences:

    *   `issueType` field must be set to a sub-task issue type (use `/issue/createmeta` to find sub-task issue types), and
    *   You must provide a `parent` field with the ID or key of the parent issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issue-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issue-post-openapi.md
- name: Jira Cloud REST API - Create issue
  x-api-slug: api2issue-post
  description: |-
    Creates an issue or a sub-task from a JSON representation.

    You can provide two parameters in request's body: `update` or `fields`. The fields, that can be set on an issue create operation, can be determined using the **/rest/api/2/issue/createmeta** resource. If a particular field is not configured to appear on the issue's Create screen, then it will not be returned in the createmeta response. A field validation error will occur if such field is submitted in request.

    Creating a sub-task is similar to creating an issue with the following differences:

    *   `issueType` field must be set to a sub-task issue type (use `/issue/createmeta` to find sub-task issue types), and
    *   You must provide a `parent` field with the ID or key of the parent issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issue-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2issue-post-openapi.md
- name: Jira Cloud REST API - Replace issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionidissue-delete
  description: |-
    Deselects a select list issue field option in all issues that it has been selected in. A different option can be selected to replace the deselected option. The update can also be limited to a smaller set of issues by using a JQL query.

    This is an [asynchronous method](#async). The response object will contain a link to the long-running task. For example, _https://your-domain.atlassian.net/rest/api/2/task/10127_.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionidissue-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionidissue-delete-openapi.md
- name: Jira Cloud REST API - Replace issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionidissue-delete
  description: |-
    Deselects a select list issue field option in all issues that it has been selected in. A different option can be selected to replace the deselected option. The update can also be limited to a smaller set of issues by using a JQL query.

    This is an [asynchronous method](#async). The response object will contain a link to the long-running task. For example, _https://your-domain.atlassian.net/rest/api/2/task/10127_.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionidissue-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionidissue-delete-openapi.md
- name: Jira Cloud REST API - Delete issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-delete
  description: |-
    Deletes an option from a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-delete-openapi.md
- name: Jira Cloud REST API - Delete issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-delete
  description: |-
    Deletes an option from a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-delete-openapi.md
- name: Jira Cloud REST API - Update issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-put
  description: |-
    Updates an option for a select list issue field. If the option does not exist, a new option is created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-put-openapi.md
- name: Jira Cloud REST API - Update issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-put
  description: |-
    Updates an option for a select list issue field. If the option does not exist, a new option is created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-put-openapi.md
- name: Jira Cloud REST API - Get issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-get
  description: |-
    Returns an option from a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-get-openapi.md
- name: Jira Cloud REST API - Get issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-get
  description: |-
    Returns an option from a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-get-openapi.md
- name: Jira Cloud REST API - Get visible issue field options
  x-api-slug: api2fieldfieldkeyoptionsuggestionssearch-get
  description: |-
    Returns options defined for a select list issue field that can be viewed by the currently logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionssearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionssearch-get-openapi.md
- name: Jira Cloud REST API - Get visible issue field options
  x-api-slug: api2fieldfieldkeyoptionsuggestionssearch-get
  description: |-
    Returns options defined for a select list issue field that can be viewed by the currently logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionssearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionssearch-get-openapi.md
- name: Jira Cloud REST API - Get selectable issue field options
  x-api-slug: api2fieldfieldkeyoptionsuggestionsedit-get
  description: |-
    Returns options defined for a select list issue field that can be viewed and selected by the currently logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionsedit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionsedit-get-openapi.md
- name: Jira Cloud REST API - Get selectable issue field options
  x-api-slug: api2fieldfieldkeyoptionsuggestionsedit-get
  description: |-
    Returns options defined for a select list issue field that can be viewed and selected by the currently logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionsedit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionsedit-get-openapi.md
- name: Jira Cloud REST API - Create issue field option
  x-api-slug: api2fieldfieldkeyoption-post
  description: |-
    Creates an option for a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoption-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoption-post-openapi.md
- name: Jira Cloud REST API - Create issue field option
  x-api-slug: api2fieldfieldkeyoption-post
  description: |-
    Creates an option for a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoption-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoption-post-openapi.md
- name: Jira Cloud REST API - Get all issue field options
  x-api-slug: api2fieldfieldkeyoption-get
  description: |-
    Returns all options defined for a select list issue field. A select list issue field is a type of [issue field](https://developer.atlassian.com/cloud/jira/platform/modules/issue-field/) that allows a user to select an value from a list of options.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoption-get-openapi.md
- name: Jira Cloud REST API - Get all issue field options
  x-api-slug: api2fieldfieldkeyoption-get
  description: |-
    Returns all options defined for a select list issue field. A select list issue field is a type of [issue field](https://developer.atlassian.com/cloud/jira/platform/modules/issue-field/) that allows a user to select an value from a list of options.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/atlassian/api2fieldfieldkeyoption-get-openapi.md
x-common:
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/platform/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/confluence/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/software/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/service-desk/swagger.v3.json
- type: x-website
  url: http://atlassian.com/
- type: x-website
  url: http://www.atlassian.com
- type: x-api-gallery
  url: http://att.dev.program.api.gallery.streamdata.io
- type: x-api-stack
  url: http://atlassian.stack.network
- type: x-blog
  url: http://blogs.atlassian.com/
- type: x-crunchbase
  url: https://crunchbase.com/organization/atlassian
- type: x-crunchbase
  url: http://www.crunchbase.com/company/atlassian
- type: x-email
  url: copyright@atlassian.com
- type: x-email
  url: trademarks@atlassian.com
- type: x-email
  url: sales@atlassian.com
- type: x-email
  url: ar_enterprise@atlassian.com
- type: x-email
  url: privacy@atlassian.com
- type: x-email
  url: eudatarep@atlassian.com
- type: x-email
  url: experts@atlassian.com
- type: x-email
  url: remittance@atlassian.com
- type: x-email
  url: ap@atlassian.com
- type: x-email
  url: procurement@atlassian.com
- type: x-github
  url: https://github.com/atlassian
- type: x-privacy-policy
  url: https://www.atlassian.com/legal/privacy-policy?_ga=2.188884514.868776184.1519225620-845241124.1519225620
- type: x-twitter
  url: https://twitter.com/atlassian
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---