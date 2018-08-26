---
name: Box
x-slug: box
description: Box is changing how you manage content across your business from simple
  file sharing to building custom apps.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
x-kinRank: "9"
x-alexaRank: "445"
tags: Collaborations
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborations/master/_listings/box/apis.md
specificationVersion: "0.14"
apis:
- name: Box - Get File's Collaborations
  x-api-slug: filesfile-idcollaborations-get
  description: Use this to get a list of all the collaborations on a file
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0
  tags: Files, Collaboration, Sharing, Storage, Storage, Stack Network, Stack, Productivity,
    SaaS, Technology, Enterprise, API Provider, Profiles, Publish, Service API, Relative
    Data, Relative StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborations/master/_listings/box/filesfile-idcollaborations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborations/master/_listings/box/filesfile-idcollaborations-get-openapi.md
- name: Box - Get Folder Collaborations
  x-api-slug: foldersfolder-idcollaborations-get
  description: Use this to get a list of all the collaborations on a folder i.e. all
    of the users that have access to that folder.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0
  tags: Files, Collaboration, Sharing, Storage, Storage, Stack Network, Stack, Productivity,
    SaaS, Technology, Enterprise, API Provider, Profiles, Publish, Service API, Relative
    Data, Relative StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborations/master/_listings/box/foldersfolder-idcollaborations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborations/master/_listings/box/foldersfolder-idcollaborations-get-openapi.md
- name: Box - Pending Collaborations
  x-api-slug: collaborations-get
  description: Used to retrieve all pending collaboration invites for this user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0
  tags: Files, Collaboration, Sharing, Storage, Storage, Stack Network, Stack, Productivity,
    SaaS, Technology, Enterprise, API Provider, Profiles, Publish, Service API, Relative
    Data, Relative StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborations/master/_listings/box/collaborations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborations/master/_listings/box/collaborations-get-openapi.md
- name: Box - Get Collaboration
  x-api-slug: collaborationscollab-id-get
  description: Used to get information about a single collaboration. All collaborations
    for a single folder can be retrieved through GET /folders/{id}/collaborations.
    A complete list of the user???s pending collaborations can also be retrieved.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0
  tags: Files, Collaboration, Sharing, Storage, Storage, Stack Network, Stack, Productivity,
    SaaS, Technology, Enterprise, API Provider, Profiles, Publish, Service API, Relative
    Data, Relative StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborations/master/_listings/box/collaborationscollab-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborations/master/_listings/box/collaborationscollab-id-get-openapi.md
- name: Box - Delete Collaboration
  x-api-slug: collaborationscollab-id-delete
  description: Used to delete a single collaboration.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0
  tags: Files, Collaboration, Sharing, Storage, Storage, Stack Network, Stack, Productivity,
    SaaS, Technology, Enterprise, API Provider, Profiles, Publish, Service API, Relative
    Data, Relative StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborations/master/_listings/box/collaborationscollab-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborations/master/_listings/box/collaborationscollab-id-delete-openapi.md
- name: Box - Get Collaborations for Group
  x-api-slug: groupsgroup-idcollaborations-get
  description: Retrieves all of the group collaborations for a given group. Note this
    is only available to group admins.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/162-box.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0
  tags: Files, Collaboration, Sharing, Storage, Storage, Stack Network, Stack, Productivity,
    SaaS, Technology, Enterprise, API Provider, Profiles, Publish, Service API, Relative
    Data, Relative StreamRank, Streams, Backups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborations/master/_listings/box/groupsgroup-idcollaborations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/collaborations/master/_listings/box/groupsgroup-idcollaborations-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://botify.api.gallery.streamdata.io
- type: x-api-stack
  url: http://box.stack.network
- type: x-base
  url: https://api.box.com/
- type: x-blog
  url: http://blog.box.com/
- type: x-blog-rss
  url: http://blog.box.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/box
- type: x-crunchbase
  url: https://crunchbase.com/organization/box
- type: x-developer
  url: http://developers.box.com
- type: x-github
  url: https://github.com/box
- type: x-pricing
  url: https://developers.box.com/box-platform-pricing/
- type: x-road-map
  url: https://developers.box.com/roadmap/
- type: x-twitter
  url: https://twitter.com/BoxPlatform
- type: x-twitter
  url: https://twitter.com/BoxHQ
- type: x-website
  url: http://box.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---