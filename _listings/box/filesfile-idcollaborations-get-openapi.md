---
swagger: "2.0"
x-collection-name: Box
x-complete: 0
info:
  title: Box Get File's Collaborations
  description: Use this to get a list of all the collaborations on a file
  version: 1.0.0
host: api.box.com
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /files/{FILE_ID}/collaborations:
    get:
      summary: Get File's Collaborations
      description: Use this to get a list of all the collaborations on a file
      operationId: getFileCollaborations
      x-api-path-slug: filesfile-idcollaborations-get
      parameters:
      - in: query
        name: fields
        description: Attribute(s) to include in the response
      - in: path
        name: FILE_ID
      - in: query
        name: limit
        description: The maximum number of items to return in a page
      - in: query
        name: offset
        description: The item at which to begin the response
      responses:
        200:
          description: OK
      tags:
      - Documents
      - Files
      - File
      - ""
      - Collaborations
x-streamrank:
  polling_total_time_average: "0"
  polling_size_download_average: "0"
  streaming_total_time_average: "0"
  streaming_size_download_average: "0"
  change_yes: "0"
  change_no: "0"
  time_percentage: "0"
  size_percentage: "0"
  change_percentage: "200"
  last_run: ~
  days_run: "0"
  minute_run: "0"
---