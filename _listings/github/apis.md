---
name: GitHub
x-slug: github
description: With a community of more than 10 million people, developers can discover,
  use and contribute to over 24 million projects using a powerful, collaborative workflow.    Whether
  using GitHub.com or your own instance of GitHub Enterprise, you can integrate ...
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
x-kinRank: "10"
x-alexaRank: "70"
tags: Issues
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/apis.md
specificationVersion: "0.14"
apis:
- name: Github Get Issues
  x-api-slug: github
  description: |-
    List issues.
    List all issues across all the authenticated user's visible repositories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////issues
  tags: Issues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/issues-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/issues-get-openapi.md
- name: Github Get Legacy Issues Search Owner Repository State Keyword
  x-api-slug: github
  description: Find issues by state and keyword.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////legacy/issues/search/{owner}/{repository}/{state}/{keyword}
  tags: Legacy, Issues, Search, Owner, Repository, State, Keyword
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/legacyissuessearchownerrepositorystatekeyword-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/legacyissuessearchownerrepositorystatekeyword-get-openapi.md
- name: Github Get Orgs Org Issues
  x-api-slug: github
  description: |-
    List issues.
    List all issues for a given organization for the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/issues
  tags: Orgs, Org, Issues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/orgsorgissues-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/orgsorgissues-get-openapi.md
- name: Github Get Repos Owner Repo Issues
  x-api-slug: github
  description: List issues for a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues
  tags: Repos, Owner, Repo, Issues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissues-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissues-get-openapi.md
- name: Github Add Repos Owner Repo Issues
  x-api-slug: github
  description: |-
    Create an issue.
    Any user with pull access to a repository can create an issue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues
  tags: Repos, Owner, Repo, Issues
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissues-post-openapi.md
- name: Github Get Repos Owner Repo Issues Comments
  x-api-slug: github
  description: List comments in a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/comments
  tags: Repos, Owner, Repo, Issues, Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuescomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuescomments-get-openapi.md
- name: Github Delete Repos Owner Repo Issues Comments Comment
  x-api-slug: github
  description: Delete a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/comments/{commentId}
  tags: Repos, Owner, Repo, Issues, Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuescommentscommentid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuescommentscommentid-delete-openapi.md
- name: Github Get Repos Owner Repo Issues Comments Comment
  x-api-slug: github
  description: Get a single comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/comments/{commentId}
  tags: Repos, Owner, Repo, Issues, Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuescommentscommentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuescommentscommentid-get-openapi.md
- name: Github Patch Repos Owner Repo Issues Comments Comment
  x-api-slug: github
  description: Edit a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/comments/{commentId}
  tags: Repos, Owner, Repo, Issues, Comments, Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuescommentscommentid-patch-openapi.md
- name: Github Get Repos Owner Repo Issues Events
  x-api-slug: github
  description: List issue events for a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/events
  tags: Repos, Owner, Repo, Issues, Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuesevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuesevents-get-openapi.md
- name: Github Get Repos Owner Repo Issues Events Event
  x-api-slug: github
  description: Get a single event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/events/{eventId}
  tags: Repos, Owner, Repo, Issues, Events, Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissueseventseventid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissueseventseventid-get-openapi.md
- name: Github Get Repos Owner Repo Issues Number
  x-api-slug: github
  description: Get a single issue
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}
  tags: Repos, Owner, Repo, Issues, Number
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuesnumber-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuesnumber-get-openapi.md
- name: Github Patch Repos Owner Repo Issues Number
  x-api-slug: github
  description: |-
    Edit an issue.
    Issue owners and users with push access can edit an issue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}
  tags: Repos, Owner, Repo, Issues, Number
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuesnumber-patch-openapi.md
- name: Github Get Repos Owner Repo Issues Number Comments
  x-api-slug: github
  description: List comments on an issue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}/comments
  tags: Repos, Owner, Repo, Issues, Number, Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuesnumbercomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuesnumbercomments-get-openapi.md
- name: Github Add Repos Owner Repo Issues Number Comments
  x-api-slug: github
  description: Create a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}/comments
  tags: Repos, Owner, Repo, Issues, Number, Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuesnumbercomments-post-openapi.md
- name: Github Get Repos Owner Repo Issues Number Events
  x-api-slug: github
  description: List events for an issue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}/events
  tags: Repos, Owner, Repo, Issues, Number, Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuesnumberevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuesnumberevents-get-openapi.md
- name: Github Delete Repos Owner Repo Issues Number Labels
  x-api-slug: github
  description: Remove all labels from an issue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}/labels
  tags: Repos, Owner, Repo, Issues, Number, Labels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuesnumberlabels-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuesnumberlabels-delete-openapi.md
- name: Github Get Repos Owner Repo Issues Number Labels
  x-api-slug: github
  description: List labels on an issue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}/labels
  tags: Repos, Owner, Repo, Issues, Number, Labels
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuesnumberlabels-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuesnumberlabels-get-openapi.md
- name: Github Add Repos Owner Repo Issues Number Labels
  x-api-slug: github
  description: Add labels to an issue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}/labels
  tags: Repos, Owner, Repo, Issues, Number, Labels
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuesnumberlabels-post-openapi.md
- name: Github Put Repos Owner Repo Issues Number Labels
  x-api-slug: github
  description: |-
    Replace all labels for an issue.
    Sending an empty array ([]) will remove all Labels from the Issue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}/labels
  tags: Repos, Owner, Repo, Issues, Number, Labels
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuesnumberlabels-put-openapi.md
- name: Github Delete Repos Owner Repo Issues Number Labels Name
  x-api-slug: github
  description: Remove a label from an issue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}/labels/{name}
  tags: Repos, Owner, Repo, Issues, Number, Labels, Name
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuesnumberlabelsname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/reposownerrepoissuesnumberlabelsname-delete-openapi.md
- name: Github Get Search Issues
  x-api-slug: github
  description: Find issues by state and keyword. (This method returns up to 100 results
    per page.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////search/issues
  tags: Search, Issues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/searchissues-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/searchissues-get-openapi.md
- name: Github Get User Issues
  x-api-slug: github
  description: |-
    List issues.
    List all issues across owned and member repositories for the authenticated
    user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/issues
  tags: User, Issues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/userissues-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/userissues-get-openapi.md
- name: Github
  x-api-slug: github
  description: With a community of more than 10 million people, developers can discover,
    use and contribute to over 24 million projects using a powerful, collaborative
    workflow.    Whether using GitHub.com or your own instance of GitHub Enterprise,
    you can integrate ...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com//
  tags: Issues
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/issues/master/_listings/github/openapi.md
x-common:
- type: x--net-library
  url: https://github.com/octokit/octokit.net
- type: x-base
  url: https://api.github.com
- type: x-blog
  url: http://github.com/blog
- type: x-blog-rss
  url: https://github.com/blog/subscribe
- type: x-change-log
  url: https://developer.github.com/changes/
- type: x-contact-form
  url: https://github.com/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/github
- type: x-crunchbase
  url: https://crunchbase.com/organization/github
- type: x-developer
  url: https://developer.github.com/
- type: x-github
  url: https://github.com/github
- type: x-guides
  url: https://developer.github.com/guides/
- type: x-ios-sdk
  url: https://github.com/octokit/octokit.objc
- type: x-pricing
  url: https://github.com/pricing
- type: x-privacy
  url: http://help.github.com/privacy-policy/
- type: x-ruby-library
  url: https://github.com/octokit/octokit.rb
- type: x-security
  url: http://help.github.com/security/
- type: x-status
  url: https://status.github.com/
- type: x-terms-of-service
  url: http://help.github.com/terms-of-service/
- type: x-transparency-report
  url: https://github.com/blog/1987-github-s-2014-transparency-report
- type: x-twitter
  url: https://twitter.com/github
- type: x-webhooks
  url: https://developer.github.com/webhooks/
- type: x-website
  url: https://github.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---