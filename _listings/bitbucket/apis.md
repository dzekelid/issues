---
name: Bitbucket
x-slug: bitbucket
description: Collaborate on code with inline comments and pull requests. Manage and
  share your Git repositories to build and ship software, as a team.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
x-kinRank: "8"
x-alexaRank: "901"
tags: Issues
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/apis.md
specificationVersion: "0.14"
apis:
- name: Bitbucket Get Repositories Username Repo Slug Issues
  x-api-slug: bitbucket
  description: Get repositories username repo slug issues
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues
  tags: Repositories, Username, Repo, Slug, Issues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissues-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissues-get-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Issues
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug issues
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues
  tags: Repositories, Username, Repo, Slug, Issues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissues-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissues-parameters-openapi.md
- name: Bitbucket Add Repositories Username Repo Slug Issues
  x-api-slug: bitbucket
  description: |-
    Creates a new issue.

    This call requires authentication. Private repositories or private
    issue trackers require the caller to authenticate with an account that
    has appropriate authorisation.

    The authenticated user is used for the issue's `reporter` field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues
  tags: Repositories, Username, Repo, Slug, Issues
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissues-post-openapi.md
- name: Bitbucket Delete Repositories Username Repo Slug Issues Issue
  x-api-slug: bitbucket
  description: |-
    Deletes the specified issue. This requires write access to the
    repository.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}
  tags: Repositories, Username, Repo, Slug, Issues, Issue
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-id-delete-openapi.md
- name: Bitbucket Get Repositories Username Repo Slug Issues Issue
  x-api-slug: bitbucket
  description: Get repositories username repo slug issues issue
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}
  tags: Repositories, Username, Repo, Slug, Issues, Issue
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-id-get-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Issues Issue
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug issues issue
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}
  tags: Repositories, Username, Repo, Slug, Issues, Issue
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-id-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-id-parameters-openapi.md
- name: Bitbucket Get Repositories Username Repo Slug Issues Issue  Attachments
  x-api-slug: bitbucket
  description: |-
    Returns all attachments for this issue.

    This returns the files' meta data. This does not return the files'
    actual contents.

    The files are always ordered by their upload date.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}/attachments
  tags: Repositories, Username, Repo, Slug, Issues, Issue, , Attachments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idattachments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idattachments-get-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Issues Issue  Attachments
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug issues issue  attachments
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}/attachments
  tags: Repositories, Username, Repo, Slug, Issues, Issue, , Attachments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idattachments-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idattachments-parameters-openapi.md
- name: Bitbucket Add Repositories Username Repo Slug Issues Issue  Attachments
  x-api-slug: bitbucket
  description: |-
    Upload new issue attachments.

    To upload files, perform a `multipart/form-data` POST containing one
    or more file fields.

    When a file is uploaded with the same name as an existing attachment,
    then the existing file will be replaced.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}/attachments
  tags: Repositories, Username, Repo, Slug, Issues, Issue, , Attachments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idattachments-post-openapi.md
- name: Bitbucket Delete Repositories Username Repo Slug Issues Issue  Attachments
    Path
  x-api-slug: bitbucket
  description: Delete repositories username repo slug issues issue  attachments path
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}/attachments/{path}
  tags: Repositories, Username, Repo, Slug, Issues, Issue, , Attachments, Path
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idattachmentspath-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idattachmentspath-delete-openapi.md
- name: Bitbucket Get Repositories Username Repo Slug Issues Issue  Attachments Path
  x-api-slug: bitbucket
  description: |-
    Returns the contents of the specified file attachment.

    Note that this endpoint does not return a JSON response, but instead
    returns a redirect pointing to the actual file that in turn will return
    the raw contents.

    The redirect URL contains a one-time token that has a limited lifetime.
    As a result, the link should not be persisted, stored, or shared.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}/attachments/{path}
  tags: Repositories, Username, Repo, Slug, Issues, Issue, , Attachments, Path
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idattachmentspath-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idattachmentspath-get-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Issues Issue  Attachments
    Path
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug issues issue  attachments
    path
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}/attachments/{path}
  tags: Repositories, Username, Repo, Slug, Issues, Issue, , Attachments, Path
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idattachmentspath-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idattachmentspath-parameters-openapi.md
- name: Bitbucket Get Repositories Username Repo Slug Issues Issue  Comments
  x-api-slug: bitbucket
  description: |-
    Returns all comments that were made on the specified issue.

    The default sorting is oldest to newest and can be overridden with
    the `sort` query parameter.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}/comments
  tags: Repositories, Username, Repo, Slug, Issues, Issue, , Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idcomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idcomments-get-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Issues Issue  Comments
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug issues issue  comments
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}/comments
  tags: Repositories, Username, Repo, Slug, Issues, Issue, , Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idcomments-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idcomments-parameters-openapi.md
- name: Bitbucket Get Repositories Username Repo Slug Issues Issue  Comments Comment
  x-api-slug: bitbucket
  description: Get repositories username repo slug issues issue  comments comment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}/comments/{comment_id}
  tags: Repositories, Username, Repo, Slug, Issues, Issue, , Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idcommentscomment-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idcommentscomment-id-get-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Issues Issue  Comments
    Comment
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug issues issue  comments comment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}/comments/{comment_id}
  tags: Repositories, Username, Repo, Slug, Issues, Issue, , Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idcommentscomment-id-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idcommentscomment-id-parameters-openapi.md
- name: Bitbucket Delete Repositories Username Repo Slug Issues Issue  Vote
  x-api-slug: bitbucket
  description: Delete repositories username repo slug issues issue  vote
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}/vote
  tags: Repositories, Username, Repo, Slug, Issues, Issue, , Vote
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idvote-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idvote-delete-openapi.md
- name: Bitbucket Get Repositories Username Repo Slug Issues Issue  Vote
  x-api-slug: bitbucket
  description: |-
    Check whether the authenticated user has voted for this issue.
    A 204 status code indicates that the user has voted, while a 404
    implies they haven't.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}/vote
  tags: Repositories, Username, Repo, Slug, Issues, Issue, , Vote
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idvote-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idvote-get-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Issues Issue  Vote
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug issues issue  vote
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}/vote
  tags: Repositories, Username, Repo, Slug, Issues, Issue, , Vote
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idvote-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idvote-parameters-openapi.md
- name: Bitbucket Update Repositories Username Repo Slug Issues Issue  Vote
  x-api-slug: bitbucket
  description: |-
    Vote for this issue.

    To cast your vote, do an empty PUT. The 204 status code indicates that
    the operation was successful.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}/vote
  tags: Repositories, Username, Repo, Slug, Issues, Issue, , Vote
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idvote-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idvote-put-openapi.md
- name: Bitbucket Delete Repositories Username Repo Slug Issues Issue  Watch
  x-api-slug: bitbucket
  description: Delete repositories username repo slug issues issue  watch
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}/watch
  tags: Repositories, Username, Repo, Slug, Issues, Issue, , Watch
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idwatch-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idwatch-delete-openapi.md
- name: Bitbucket Get Repositories Username Repo Slug Issues Issue  Watch
  x-api-slug: bitbucket
  description: |-
    Indicated whether or not the authenticated user is watching this
    issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}/watch
  tags: Repositories, Username, Repo, Slug, Issues, Issue, , Watch
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idwatch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idwatch-get-openapi.md
- name: Bitbucket Parameters Repositories Username Repo Slug Issues Issue  Watch
  x-api-slug: bitbucket
  description: Parameters repositories username repo slug issues issue  watch
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}/watch
  tags: Repositories, Username, Repo, Slug, Issues, Issue, , Watch
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idwatch-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idwatch-parameters-openapi.md
- name: Bitbucket Update Repositories Username Repo Slug Issues Issue  Watch
  x-api-slug: bitbucket
  description: |-
    Start watching this issue.

    To start watching this issue, do an empty PUT. The 204 status code
    indicates that the operation was successful.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0//repositories/{username}/{repo_slug}/issues/{issue_id}/watch
  tags: Repositories, Username, Repo, Slug, Issues, Issue, , Watch
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idwatch-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/repositoriesusernamerepo-slugissuesissue-idwatch-put-openapi.md
- name: Bitbucket
  x-api-slug: bitbucket
  description: Collaborate on code with inline comments and pull requests. Manage
    and share your Git repositories to build and ship software, as a team.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/19810-bitbucket.jpg
  humanURL: http://bitbucket.org
  baseURL: https://api.bitbucket.org//2.0
  tags: Issues
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/bitbucket/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/bitbucket
- type: x-developer
  url: https://developer.atlassian.com/cloud/bitbucket/
- type: x-documentation
  url: https://confluence.atlassian.com/bitbucket/bitbucket-cloud-documentation-221448814.html?_ga=2.77295890.629375793.1519179030-1077111323.1516485126
- type: x-status
  url: https://status.bitbucket.org/?_ga=2.76365714.629375793.1519179030-1077111323.1516485126
- type: x-support
  url: https://support.atlassian.com/bitbucket-cloud/
- type: x-terms-of-service
  url: https://www.atlassian.com/legal/customer-agreement?_ga=2.76365714.629375793.1519179030-1077111323.1516485126
- type: x-twitter
  url: https://twitter.com/bitbucket
- type: x-website
  url: http://bitbucket.org
- type: x-website
  url: https://bitbucket.org/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---